# Vue

10/23


-console logs can break applications use new util logger to console log from now on. It must be imported. 

Components rather than controllers for Vue. 
- for each component there will be HTML JS and CSS
-inside the component will be your controller.

- you can inject js values directly into the html section of the vue component with double curly brackets <h1>{{3 * 3 }}</h1>



Vue CSS 
- The css is scoped ie only targets the html inside the component


Variables/ private & public 
- variables should be declared in the setup if they are only in the setup they will be private. If you want public variables you must send the variable through the return. 

- If you want functions to be public you have to put them in the return.


Ref(0) 

let cheese = ref(0)

-this makes the value be watched by listeners and when you change the value it will redraw the variable. 

cheese.value++ 
- this would cause the ref to go off and redraw. 

Appstate 
- to bring in a reactive value from the AppState you must compute them ie

cheese: computed(() => return{AppState.cheese})  or to point to one value and to short hand write
cheese: computed(() => AppState.cheese)

-in general you only want your computed to bring in only one value


V-for
- for each for view
-this allows us to create small templates inline on html rather than having to make get templates.
-this will render the element and its children with interpolated data for each piece of data in the AppState.

v-if 
-this says only render this element that it is in unless the value is true


Any on behavior can be replaced with @
- they must be used for any functions that are tied to the html in the component
-@click
-@submit


Params Args 
- entire objects can be passed down as args this can only be done in a v-for ie a forEach cause that's where you have access to it.


10/24

v-for 
in a v-for they required a v-bind key that is unique to that data ie id, name,


10/25

Components 
- You can get around building out extra components, but generally you should build them out whenever you can.

Pages

- no page should ever have props cause the pages are the parents of the components that you can pass props to
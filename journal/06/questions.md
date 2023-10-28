# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > | The first function or code that is ran when you start run the application |

02. What is the difference between a vue `component` and `page`?

  > | under the hood pages are components, but pages are used as the overall main view for that page. Components are compiled on the page to build sections of the actual application. |

03. What is ***Component-Based Architecture***?

  > | It's a method of software development that breaks down code into self contained self sufficient components. |

04. What are the three tags that make up a Vue component?

  > | <template></template>, <script></script>, <style></style> |

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > | It allows us to invoke certain methods or run code during specified points of the applications life cycle |

06. Which component in Vue does the vue-router use to mount pages onto?

  > | <router-view> |

07. What is the difference between the `AppState` and the state object within a component?

  > | the AppState is globally scoped and it is stored in a higher level of the application. A state object inside of a component is scoped to that component the entire state is also stored in the component where as the AppState is an entirely separate file.  |

08. What is the responsibility of `Services` in our Vue projects?

  > | to deal with anything that has to change the data in our appstate or db |

09. What are ***props*** and how are they used? Provide an example

  > | props are a way to pass data from a parent component to a child component. they are used by setting up what prop the child component expects then send that prop through the parent component. An example would be to pass |

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > | reactive |

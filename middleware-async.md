### Middleware - Async Behavior


#### Promises

- **redux-promise**  
  https://github.com/acdlite/redux-promise  
  FSA-compliant promise middleware for Redux.
  
- **redux-simple-promise**  
  https://github.com/alanrubin/redux-simple-promise  
  FSA-compliant promise middleware for Redux with simple behaviour with minimal boilerplate declarations.
  
- **redux-catch-promise**  
  https://github.com/DenisIzmaylov/redux-catch-promise  
  Extended replacement of redux-thunk middleware to supporting async-await functions and implement server-side rendering for React components with asynchronous state.
  
- **redux-async**  
  https://github.com/symbiont-io/redux-async  
  RSA-compliant actions which resolve when any prop is a promise middleware for Redux.
  
- **redux-promise-middleware**  
  https://github.com/pburtchaell/redux-promise-middleware  
  Redux middleware for resolving and rejecting promises with conditional optimistic updates
  
- **redux-deferred**  
  https://github.com/wyvernnot/redux-deferred  
  Redux middleware for jQuery Deferred object
  
- **redux-promises**  
  https://github.com/CrocoDillon/redux-promises  
  Promise based middleware for Redux to deal with asynchronous actions. redux-promises is backwards compatible with redux-thunk.
  
- **redux-optimist-promise**  
  https://github.com/mathieudutour/redux-optimist-promise  
  FSA-compliant promise middleware middleware for Redux and automatically add necessary for redux-optimist.
  
- **redux-async-middleware**  
  https://github.com/reducks/redux-async-middleware  
  Provides a middleware for handling asynchronous actions.
  
- **redux-pending**  
  https://github.com/adriancooney/redux-pending  
  A promise middleware that you add to your store and will handle resolving the promises and dispatching pending actions. It's based heavily around redux-promise.
  
- **redux-promised**  
  https://github.com/bobmonteverde/redux-promised  
  FSA-compliant promise middleware for redux with optimistic update support
  
- **redux-await-middleware**  
  https://github.com/zenato/redux-await-middleware  
  Await(Promise) middleware for Redux.  Await middleware supprorts FSA actions.
  
- **redux-object-to-promise**  
  https://github.com/mathieudutour/redux-object-to-promise  
  Redux middleware to transform an object into a promise
  
- **redux-payload-promise**  
  https://github.com/zavalit/redux-payload-promise  
  Async Redux Action on a Promise base
  
- **redux-loading-promise-middleware**  
  https://github.com/kallaspriit/redux-loading-promise-middleware  
  Middleware for Redux that turns promises into several dispatches of loading, success and error states, confirming to flux standard action schema.
  
- **redux-promise-loading**  
  https://github.com/amorphousxd/redux-promise-loading  
  Redux middleware and reducer for handling redux promise loading indicator
  
- **redux-pack**  
  https://github.com/lelandrichardson/redux-pack  
  Sensible promise handling and middleware for redux
  
- **redux-packa**  
  https://github.com/daniel-lundin/redux-packa  
  Wrapper around redux-pack that adds hooks and handlers for canceled promises.
  
- **redux-pinky**  
  https://github.com/themostaza/redux-pinky  
  Yet another Redux middleware for dispatching async actions.  A more "redux-vanilla" version of redux-pack.
  
- **redux-promises-concluder**  
  https://github.com/arashmilani/redux-promises-concluder  
  A Redux middleware to keep track of active promises and notify when all resolved. Useful in server side rendering of single page applications. 
  
- **redux-p**  
  https://github.com/fedor/redux-p  
  redux-p middleware accepts action type in action.type and Promise in action.payload. It was made to made to replace redux-promise-middleware for React Native.
  
- **redux-submission**  
  https://github.com/ajoslin/redux-submission  
  Pending and error states for promises in redux.  This heavily borrows from redux-pending, with error support added.
  
- **redux-promise-bind**  
  https://github.com/machnicki/redux-promise-bind  
  A promise middleware that dispatches start/success/error actions, plus metadata
  
- **redux-track-promise**  
  https://github.com/jedwards1211/redux-track-promise  
  A tiny redux library with a reducer that handles setPending, resolve, and reject actions, and a trackPromise method that takes a Promise and dispatches those actions when the promise state changes.
  
- **redux-request-status**  
  https://github.com/davidstevens37/redux-request-status  
  Provides a declarative, readable, easy to implement utility for handling asyncronous status changes. Typically, this will be an http request, but could be any asyncronous action that returns a promise. Using redux-request-status we're able to respond to 3 different actions by ( onRequest, onSuccess, or onError ) for a single action type.
  
 - **fetch-middleware**  
   https://github.com/arojunior/fetch-middleware  
   Despite the name, actually just dispatches start/success/error actions based on a promise
  
  
#### Timeouts and Delays

- **redux-timeout**  
  https://github.com/gpfunk/redux-timeout  
  Gives ability to call functions if certain actions have not been dispatched in x amount of time.
  
- **redux-trigger**  
  https://github.com/coderkevin/redux-trigger  
  a Redux middleware which allows delayed dispatching of an action based on a trigger state in the Redux store.
  
- **redux-debounced**  
  https://github.com/ryanseddon/redux-debounced  
  Debounce allows you to discard a fast paced action from updating your state until a certain period of time passes after the last action is fired.
  
- **redux-delay**  
  https://github.com/Laiff/redux-delay  
  Delay redux actions
  
- **Redux Action Buffer**  
  https://github.com/rt2zz/redux-action-buffer  
  A middleware for redux that buffers all actions into a queue until a breaker condition is met, at which point the queue is released (i.e. actions are triggered).
  
- **Quince**  
  https://github.com/defact/quince  
  Queueing middleware for Redux.
  
- **redux-throttle-actions**  
  https://github.com/pirosikick/redux-throttle-actions  
  A Redux middleware which throttles actions.
  
- **redux-debounce**  
  https://github.com/wyze/redux-debounce  
  A middleware for Redux to debounce actions.
  
- **redux-async-queue**  
  https://github.com/zackargyle/redux-async-queue  
  ReduxAsyncQueue middleware makes queueing redux actions painless. This allows you to fire multiple actions simultaneously and have them execute asynchronously in order. 
  
- **redux-throttle**  
  https://github.com/mathieudutour/redux-throttle  
  Redux middleware to throttle your actions
  
- **optimistic-middleware**  
  https://github.com/Workpop/optimistic-middleware  
  Optimistically apply actions that will be reverted on error.
  
- **redux-queue-offline**  
  https://github.com/mathieudutour/redux-queue-offline  
  Queue actions when offline and dispatch them when getting back online.
  
- **redux-q**  
  https://github.com/ConciergeAuctions/redux-q  
  redux-q lets you enqueue any function in a queue that is mapped to an action type. The next time that action is dispatched each callback will be called with that action and the queue will be cleared.
  
- **Redux Optimistic Actions**  
  https://github.com/Audicy/redux-optimistic-actions  
  Middleware for managing optimistic actions based on promises
  
- **redux-optimistic**  
  https://github.com/conorhastings/redux-optimistic  
  Simple, user controlled optimistic updates for redux. 
  
- **redux-enqueue**  
  https://github.com/jacobp100/redux-enqueue  
  Simple queue system for redux. Use with redux-thunk.
  
- **redux-trigger-middleware**  
  https://github.com/saintcrawler/redux-trigger-middleware  
  Middleware that lets you call predefined functions on certain actions.
  
- **redux-delayed-dispatch**  
  https://github.com/beaucollins/redux-delayed-dispatch  
  Delayed Dispatch is setTimeout/clearTimeout but in middleware form with some small enhancements.
  
- **redux-timer-middleware**  
  https://github.com/matpaul/redux-timer-middleware  
  Simple middleware to dispatch actions periodically
  
- **redux-when**  
  https://github.com/jameslnewell/redux-when  
  Redux middleware for delaying dispatch of an action until a condition evaluates to true.
  
- **redux-memoize**  
  https://github.com/kouhin/redux-memoize  
  Memoize action creator for redux, and let you dispatch common/thunk/promise/async action whenever you want to, without worrying about duplication.  Useful for de-duplicating requests. 
  
- **redux-bus**  
  https://github.com/challenger532/redux-bus  
  A middleware for redux that makes it easy to create buffers with handlers
  
- **redux-promise-queue**  
  https://github.com/detrash08/redux-promise-queue-middleware  
  A simple redux middleware to chain independent async actions calls
  
- **redux-reqres**  
  https://github.com/Shotzoom/redux-reqres  
  Request response synchronization middleware. Syncronization should be used when multiple async actions may be dispatched to fetch data, but only the last response should be serviced such as type aheads and search filtering.
  
  
#### Other Async Actions
  
- **redux-await**  
  https://github.com/kolodny/redux-await  
  Manage async redux actions sanely.  This module exposes a middleware, reducer, and connector to take care of async state in a redux app.

- **redux-future**  
  https://github.com/stoeffel/redux-future  
  FSA-compliant future monad middleware for Redux, based on redux-promise.
  
- **redux-either**  
  https://github.com/stoeffel/redux-either  
  FSA-compliant either monad middleware for Redux, based on redux-future.
  
- **redux-wait**  
  https://github.com/ForbesLindesay/redux-wait  
  A helper to let you wait for redux actions to be processed in a universal app.
  
- **redux-save**  
  https://github.com/Legitcode/redux-save  
  Full featured middleware for handling async actions and automagically saving data (For RN & Web)
  
- **redux-notify**  
  https://github.com/zalmoxisus/redux-notify  
  Redux middleware to notify when an action from the list is dispatched.
  
- **redux-co**  
  https://github.com/kilianc/redux-co  
  redux-co is a drop-in replacement for redux-thunk (and indeed passes its test suite). It's meant to support async actions through yieldables as well as plain thunk functions.
  
- **Redux Thunk Inject**  
  https://github.com/producthunt/redux-thunk-inject  
  A drop-in replacement for redux-thunk that lets you inject additional variables into your action creators.
  
- **redux-fsa-thunk**  
  https://github.com/jtpalmer/redux-fsa-thunk  
  FSA-compliant thunk middleware for Redux.
  
- **redux-method-middleware**  
  https://github.com/abhiaiyer91/redux-method-middleware  
  Similar to Promise Middleware, handle asynchronous callback functions via Redux Middleware
  
- **redux-codi**  
  https://github.com/laat/redux-codi  
  Redux middleware with dependency injection and async control flow.  Enables async/await style actions with co, and simple dependency injection in the middleware creator.
  
- **redux-di**  
  https://github.com/laat/redux-di  
  Thunk middleware with dependency injection
  
- **redux-sync-promise**  
  https://github.com/shanhaichik/redux-sync-promise  
  Middleware for writing asynchronous actions in synchronous style
  
- **wait-for-redux-thunk**  
  https://github.com/kkotlarski/wait-for-redux-thunk  
  Simple middleware providing hooks after every async action and a final callback when all async actions are completed. Very useful when building universal react applications with redux-thunk.

- **redux-generator-thunk**  
  https://github.com/geckoboard/redux-generator-thunk  
  Allows you to write action creators that return a generator function instead of an action.
  
- **redux-pull-actors**  
  https://github.com/nrn/redux-pull-actors  
  Middleware for doing additional asynchronous work based on redux actions and state transitions.
  
- **redux-iterators**  
  https://github.com/aabenoja/redux-iterators  
  Redux middleware for handling action creators that return iterators
  
- **Redux Triple Barreled Actions**  
  https://github.com/davidfurlong/redux-triple-barreled-actions  
  Redux Middleware which provides a syntax for dispatching async actions
  
- **Redux Service**  
  https://github.com/ThatBean/redux-service  
  Service middleware for Redux.
  
- **redux-seq-dispatch**  
  https://github.com/dayzhou/redux-seq-dispatch  
  Redux middleware for dispatching promise- or array-valued actions
  
- **redux-amrc**  
  https://github.com/lewis617/redux-amrc  
  Redux async middleware and reducer creator for dispatching async actions with less boilerplate.
  
- **redux-middleware-async**  
  https://github.com/robinpowered/redux-middleware-async  
  Redux middleware for performing predictable asynchronous actions.
  
- **redux-generator**  
  https://github.com/xuyuanxiang/redux-generator  
  Middleware for redux to resolve generator function actions.  
  
- **redux-sane**  
  https://github.com/xiaody/redux-sane  
  A redux middleware that provides sane default behaviors for non-object actions. Dispatch whatever you like: function(thunk)/promise/generator.
  
- **redux-client-middleware**  
  https://github.com/intactile/redux-client-middleware  
  A redux middleware handling async client actions.  Acts like a combination of redux-thunk and a promise middleware.
  
- **redux-roll**  
  https://github.com/vgabor/redux-roll  
  Redux-roll lets you dispatch chained functions and promises, and also allow you to mix-and-match functions and promises together. 
  
- **redux-async-thunk**  
  https://github.com/kutlugsahin/redux-async-thunk  
  Expension for Redux thunk middleware to support AsyncFunction and GeneratorFunction types to enable async/await generator/yield syntax 
  
- **redux-generator-action**  
  https://github.com/Mrlyjoutlook/redux-generator-action  
  A generator-based action flow control middleware
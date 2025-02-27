# Changelog

- **7.0.1** - Code clean up
- **7.0.0** - Performance impove, dynamicSpawn
- **6.3.1** - Code clean up
- **6.2.0** - Gentle execution with port feature and bug fixes
- **6.1.0** - Introduced gentle execution feature
- **6.0.5** - Logger fix
- **6.0.4** - Dart version bump and library declaration refactor
- **6.0.3** - Readme fix
- **6.0.2** - Fix for port communication in the new Dart version
- **6.0.1** - Export fix for web
- **6.0.0** - Introduced Dart 3 features, optimizations, and code refactoring
- **5.0.3** - Version bump and bug fix for notifications
- **5.0.0** - Implemented messages communication between isolates (tasks)
- **4.5.0** - Reverted to old async for Flutter tests
- **4.4.8** - Web fix with initialized getter
- **4.4.7** - Fixed bug with cancelling the first task during cold start
- **4.4.6** - TypeSendPort placeholder for fake execution
- **4.4.2** - Introduced web support with SendPort's new API
- **4.4.0** - Notification from isolate via SendPort
- **4.3.1** - Cold start fix
- **4.3.0** - Introduced pause and resume capabilities for cancelable and Executors pool
- **4.2.6** - Fixed all errors case bug and improved testing
- **4.2.4** - Readme update and example fix
- **4.1.1** - Fake isolate fix
- **4.1.0** - Removed onNext
- **4.0.0** - Introduced null safety
- **3.2.6** - Added Cancelable.fromFuture constructor
- **3.2.4** - Fixed onNext value null calling
- **3.2.0** - Introduced static mergeAll method
- **3.1.9** - Added mergeAll method
- **3.1.7** - Readme fix
- **3.1.6** - Readme update with explanation of how to use onValue and onNext callback and why
- **2.8.4** - Edited cancelable to be more like then callback
- **2.8.3** - Introduced fake execute method
- **2.6.6** - Added "next" method to chain result with next Cancelable
- **2.6.0** - Reverted value
- **2.5.9** - Removed value from Cancelable
- **2.5.4** - Cancelable now implements Future
- **2.5.3** - Changed cancelableOperation to Cancelable
- **2.5.0** - Warm up required
- **2.4.1** - Readme update and removed unnecessary wrappers
- **2.4.1** - Introduced cancelable operation
- **2.3.6** - Changed return type in addTask. (Still possible to wrap as Stream from future)
- **2.3.0** - Introduced runnable
- **2.1.4** - Optimized task removal
- **2.0.9** - Introduced task types
- **2.0.7** - Readme update and dependencies
- **2.0.5** - Implemented FIFO adding
- **2.0.4** - Code clean up
- **2.0.1** - Removed ghost
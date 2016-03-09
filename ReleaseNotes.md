# 2.1 #

Release date: 22nd August 2009

  * Renamed all `Allow()` methods to `Permit()` in keeping with `PermittedTriggers` property name and terminology shared with other frameworks
  * Parameterised triggers: `StateMachine.SetTriggerParameters()` and the `OnEntryFrom()` methods
  * `OnEntry()` and `OnExit()` overloads added to accept `Action` (not just `Action<Transition>`)
  * Internal refactoring, cleanup, performance and test improvements

# 1.3 #

First binary release.
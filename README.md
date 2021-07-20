# yarn2-unregistered-root-repro
Reproduction of Yarn 2 Error: "Assertion failed: Expected the root to be registered"

Run `yarn install`

```
➤ YN0000: ┌ Resolution step
➤ YN0001: │ Error: Assertion failed: Expected the root to be registered
    at applyVirtualResolutionMutations (/.../yarn2-unregistered-root-repro/.yarn/releases/yarn-sources.cjs:67492:15)
    at Project.resolveEverything (/.../yarn2-unregistered-root-repro/.yarn/releases/yarn-sources.cjs:66566:7)
    at processTicksAndRejections (internal/process/task_queues.js:95:5)
    at async /.../yarn2-unregistered-root-repro/.yarn/releases/yarn-sources.cjs:67001:9
    at async StreamReport.startTimerPromise (/.../yarn2-unregistered-root-repro/.yarn/releases/yarn-sources.cjs:63184:16)
    at async Project.install (/.../yarn2-unregistered-root-repro/.yarn/releases/yarn-sources.cjs:67000:7)
    at async /.../yarn2-unregistered-root-repro/.yarn/releases/yarn-sources.cjs:69971:9
    at async Function.start (/.../yarn2-unregistered-root-repro/.yarn/releases/yarn-sources.cjs:63104:9)
    at async YarnCommand.execute (/.../yarn2-unregistered-root-repro/.yarn/releases/yarn-sources.cjs:69965:22)
    at async YarnCommand.validateAndExecute (/.../yarn2-unregistered-root-repro/.yarn/releases/yarn-sources.cjs:57689:24)
➤ YN0000: └ Completed in 0s 446ms
➤ YN0000: Failed with errors in 0s 450ms
```

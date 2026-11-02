# /nexo-board

Nexo Apps' public command for the inherited application factory.

During the migration, `/nexo-board` delegates to the proven `super-board`
implementation. The compatibility command remains available internally so the
factory can be renamed in stages without losing existing projects or state.

| Command | Does |
|---|---|
| `/nexo-board onboard` | Configures the application factory |
| `/nexo-board lint` | Checks whether work items are ready |
| `/nexo-board status` | Shows the current board state |
| `/nexo-board run` | Runs Build → QA → Review |
| `/nexo-board stop` | Stops a running factory safely |

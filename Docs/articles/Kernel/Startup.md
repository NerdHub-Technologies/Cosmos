# Startup

On startup, there is some hand-coded assembly that runs before the Cosmos layer kicks in. From there, the C# entry point Cosmos.System.Kernel.Start(); or Sys.Kernel.Start(); is called.

Cosmos.System.Kernel is an abstract class that forms the Cosmos framework upon which your OS is built upon.

You can override the Kernel.Start() method to suppress the standard Cosmos boot routines.

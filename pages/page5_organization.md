Organization {#organization}
------------

This project is (since 2015-07-11) split into several repositories to encapsulate
the behavior of its individual components. Each repository has its own purpose
and should not be treated like sourcecode dumping-sites.

You can find all the repositories on the [organization page](https://github.com/Pigaco). 

The most important repositories are:

  * [libpiga](https://github.com/Pigaco/libpiga): Holds the connecting library for the console.
  * [Console](https://github.com/Pigaco/Console): Holds the Pigaco-Console application, which hosts
    every game on the platform and distributes commands from all sources to the specified applcations
    and games.
  * [networked_client](https://github.com/Pigaco/networked_client): Holds a networked client program &
    library, which can be used to send commands to a console over the network.
  * [hosts](https://github.com/Pigaco/hosts): Holds a system to encapsulate the behavior of a 
    host (a machine which gives inputs), which can be implemented independently to the rest of the system.

# Singleton Pattern


## Leftover work
> Making it extensible and generic.
> Serialization

## Use case
Sometimes it's required to have only one instance of a class. For example
- In a system there should be only one window manager.
- Logger Classes
- Configuration Classes and many more.

## Implementation
There are many points which needs to be considered while singleton implentation
However in existing implementation not all the points are considered. But it can
be treated as good start to implement other requirements.
- Dealing with multithreaded enviroment.
- Lazy instantiation or early instantiation.
- Return object by pointer or reference?
- Rule of 3 in C++03 and Rule of 5 in C++11 onwards.
- How to make it extensible. Benefits?
- Underyling object as static member?
- Template based?
- Dealing with serialization.

## Important links for more details
- [C++ and the Perils of Double-Checked Locking] (http://www.aristeia.com/Papers/DDJ_Jul_Aug_2004_revised.pdf)
- [C++ Singleton Design Pattern] (http://stackoverflow.com/questions/1008019/c-singleton-design-pattern)
- [Intuitive example] (http://www.yolinux.com/TUTORIALS/C++Singleton.html)


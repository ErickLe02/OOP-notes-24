GoF is gang of four

Procde a way to access the elements of an aggregate object sequentially without exposing its underlying representation

```cpp
interface Iterator {
	void first();
	void next();
	bool IsDone();
	T CurrentItem();
}
```

Often First(); is replaced by copy
Forward Iteration only
Has been generalized to many related situations

c++ standard library: Sequence Containrs
std::vector();
std::list();
std::deque();
std::array();
std::forward_list();
std::string

C++ Library: algorithms
std::copy();
std::stort();
std::search();
std::find();

C++ Iterators
Iterators tie data strctures and algorithms together

- Problem 1:
	- m algorithms
	- n containrs
	- = m x n implementations
- Problem 2:User-defined containers


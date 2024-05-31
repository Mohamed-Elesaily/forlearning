# Binding
 - what is binding? <br />
 binding is a process of associating function call wih function definition. it has two types : <br />
    1. static binding.
    2. dynamic binding.

## Static Binding 
Static binding is a process of resolving function call at compile time. Typically used for normal function call and overloaded function
```
class Student{
    public:
    int id;
    void print(){
        std::cout<< this->id << std::endl;
    }

};


int main() {
    Student S1;
    S1.id = 5;
    S1.print(); \\ normal function call
    return 0;
}
```



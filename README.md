# swift-mvvw
A Swift multiplatform MVVW Framework 


## References
- https://github.com/dsuryd/dotNetify-Nancy-demo

```swift
protocol ViewModel {
   func notifyView()
}

extension ViewModel {
   func notifyView() {
   }
   
}

class Todo {
}


class TodoViewModel : ViewModel {
   
   var todoList = [Todo]() {
       onAdded (item){
           todoRepository.save(item)
       }
   }
   var [vmPropertyIgnore] textInput:String? {
   didSet {
   
   }
   didGet {
   
   }
   }
   var [vmProperty] textInput:String? {

   }
   var todoRepository: TodoListRepository?
   
   func sumbit() {
       List.add(self.textInput)
   }
   
   
   func
   
}

```

```html

<html>

   <input type=text id="textInput" value="dsada" />
   <ul>
       <li>Criar um framework</li>
   </ul>


  <script>
  viewModel {
     
     var toloList ...
     var textInput = "dsada"
  }
  </script>
</html>
```

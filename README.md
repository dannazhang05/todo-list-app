# todo-list-app
0计算机基础小白iOS开发学习之项目练手：
不懂技术的运营不是好产品。

## 创建项目
首先，我们需要在 Xcode 中创建一个新的 SwiftUI 项目。打开 Xcode，选择 File -> New -> Project，选择 iOS Application，点击 Next。在下一个界面中，我们需要输入项目的名称、组织名称和其他一些信息。选择 SwiftUI 作为界面框架。点击 Next，选择项目的保存路径，然后点击 Create。

## 设计界面
在项目创建成功之后，我们需要设计界面。打开 ContentView.swift 文件，这是默认情况下创建的 Swift UI 视图。在这个文件中，我们可以使用一些 Swift UI 组件来构建我们的 ToDo List 界面，比如 NavigationView、List、Text、Button 等。

为了让我们的 ToDo List 界面更加美观，我们可以添加一些自定义样式，比如改变字体、颜色、边框等。我们也可以使用一些 SwiftUI 内置的样式，比如 .padding()、.foregroundColor() 等。

## 添加数据
在我们的 ToDo List 界面中，我们需要添加一些数据，比如待办事项的标题、是否已完成等信息。我们可以创建一个简单的数据模型来存储这些信息，并在 ContentView.swift 文件中使用这些数据模型。

对于这个项目，我们可以使用一个包含待办事项的数组来存储数据。为了更好地管理数据，我们可以创建一个独立的数据管理类，比如 ToDoListViewModel，用于管理待办事项的添加、删除、更新等操作。

## 添加交互
除了添加数据之外，我们还需要为我们的 ToDo List 界面添加一些交互。比如，我们需要添加一个按钮来添加新的待办事项，添加一个手势来标记待办事项已完成，添加一个按钮来删除待办事项等。

在 SwiftUI 中，我们可以使用一些内置的手势和动画来实现这些交互。比如，我们可以使用 .onTapGesture() 方法来添加一个轻击手势，使用 .onDelete() 方法来添加删除操作等。

## 状态管理
在我们的 ToDo List 界面中，我们还需要管理一些状态，比如添加待办事项的状态、编辑待办事项的状态等。为了管理这些状态，我们可以使用 Swift 的 @State、@Binding 和 @ObservedObject 等属性包装器来管理状态和属性。

除了这些属性包装器之外，我们还可以使用 SwiftUI 的 sheet 和 alert 方法来管理弹出窗口和警告框的状态。

这些就是创建一个简单的 ToDo List App 的基本步骤。当然，在实际开发中，我们需要考虑更多的细节和复杂性，比如数据的持久化、网络请求、用户身份验证等等。

# Login control demo

This example shows how to use our simple application framework. 

There is often a need to throw together a simple SystemWeaver application for a specific task. To make this fast and simple we provide a simple application framework with a login control, so that you can concentrate on creating the needed functionality.

# Building

To build this project you need to get the SystemWeaverClientAPI.dll and put it in the Imported directory.

# Note

* This example uses the application framework. If you just want the login functionality, it is contained in its own control.
* The login control remembers what servers you have been logged in to. This is stored in ...

## How to create your own application

* Create a new WPF Application.
* Add references to 
  * SystemWeaverClientAPI.dll
  * Systemite.SystemWeaver.Controls.dll
* Add an instance of the ApplicationUserControl to the MainWindow

```xml
  <xaml/>
```
* Create your control, we choose to inherit from UserControl
* Register you control with the framework
```xml
  <xaml/>
```
* Build and run. After successful login the factory method will be called and create an instance of your control which will be shown in a tab.

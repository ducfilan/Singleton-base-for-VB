# Singleton-base-for-VB
A visual basic (VB) base class for Singleton pattern implementation including Lazy initialization

# To use:

```vb
Imports [Singleton base namespace]
Namespace YourNamespace
    Public Class YourClassName : Inherits SingletonBase(Of YourClassName)
        Private Sub New()
        End Sub
        ...
    End Class
End Namespace
```

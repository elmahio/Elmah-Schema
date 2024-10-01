# Elmah-Schema

> This no longer seems to work in modern versions of Visual Studio. And since ASP.NET Core is now the new normal for creating web applications in .NET, this repository is archived.

Elmah-Schema is a simple ELMAH configuration XML Schema file originally created by Jeff Lingis. The ELMAH schema can be used to allow IntelliSense in Visual Studio, validate your web.config file or anything in relation to ELMAH's XML configuration format.

## IntelliSense

To use `Elmah.xsd` place it anywhere in your project, then add the following attribute to the `elmah` element:

```xml
<elmah xmlns="http://Elmah.Configuration">
</elmah>
```


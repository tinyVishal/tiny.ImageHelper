# tiny.ImageHelper

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

A library for modifying key attributes for EMF file.
Supports Modifying 
1. Font Color
2. Background Color
3. Convert to Black and white
4. Convert to gray scale


### Supported Version
1. .net 5
2. .net Core 3.1
3. .net framework 4.8

## Sample Code
```csharp
  Color newColor = Color.FromKnownColor(KnownColor.Red);
  var converter = new EMFConverter(_logger);
  converter.EMFFromClipboard(@"C:\temp\sample1.emf", Option.TransformFont, (newColor.R, newColor.G, newColor.B));
```
## License

MIT

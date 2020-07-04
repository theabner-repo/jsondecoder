# JSON Decoder 

Este es el repositorio de la mini serie de JSON Decoder en Swift. Podrás ver el ejemplo realizado en el video

# Introducción
Con el release de Swift 4, este incluyó dos protocolos: *__Encodable y Decodable__*. Hoy en Swift 5 solo es *__Codable__*.

# Codable
Muchas tareas que se requieren hacer dentro la app como recibir datos de un API, guardarlos, leerlos desde el disco o enviarlos, requieren conversión de estos mismos.
Swift incluye dos protocolos *__Encodable y Decodable__*, que al adoptarlos, nos permite hacer una representación de nuestros datos como *JSON*. Para soportarlos, solo basta adoptar __[Codable](https://developer.apple.com/documentation/swift/codable)__.

__Adopción__
```
struct MyStruct: Codable { 
```

# Más Información
https://www.hackingwithswift.com/articles/119/codable-cheat-sheet

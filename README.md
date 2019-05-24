# Docker [Wolfram Engine](https://www.wolfram.com/engine/)

## Usage
1. Create an account [https://account.wolfram.com/auth/create](https://account.wolfram.com/auth/create)

2. Run
```
$ docker run --rm -it vladkras/wolfram-engine
```
3. Enter your email and password when prompted

4. Try
```
In[1]:= SatelliteData[ Interpreter[ "Satellite" ][ "ISS" ], "Position" ]
```

## License
Wolfram Engine is [free](https://www.wolfram.com/engine/) for non-production use.

[Terms](http://www.wolfram.com/legal/terms/wolfram-engine.html)

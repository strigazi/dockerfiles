A dockerised version of [Weka](http://www.cs.waikato.ac.nz/ml/weka/)
## Usage
### GUI
```
docker run --rm \
	-v "$(pwd)" \
	-w "$(pwd)" \
	-e DISPLAY=$DISPLAY \
	-v /tmp/.X11-unix:/tmp/.X11-unix \
	strigazi/weka "$@"
```

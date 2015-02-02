# alphatab  

 3633 seems read chinese error from here
 
``` js
readStringIntUnused: function() {
	this._data.read(4);
	return this.readString(this._data.readByte());
}
```

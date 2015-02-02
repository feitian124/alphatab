# alphatab  

``` seems read chinese error from here
readStringIntUnused: function() {
	this._data.read(4);
	return this.readString(this._data.readByte());
}
```

## images2gif-Pillow

### update
  06/22 [fix bug](https://github.com/lucyking/images2gif-Pillow/commit/b9d2de71e42ef0805715c4c32768e7b9aacdb934):
  
    
    x0, x1 = X[0], X[-1]+1
    type(x0)
    <type 'numpy.ndarray'>
    
that lead to
    
   >C:\Python27\Lib\site-packages\images2gif\images2gif.py:347: 
    VisibleDeprecationWarning: converting an array with ndim > 0 to an index will result in an error in the future
    im2 = im[y0:y1,x0:x1]
    

### Install
- pip install [images2gif-Pillow](https://pypi.python.org/pypi/images2gif-Pillow)

### About
- Fork from **ben C**'s [images2gif](https://bitbucket.org/bench/images2gif.py) repo
- Just [modify one line](https://github.com/lucyking/images2gif-Pillow/blob/master/images2gif/images2gif.py#L426) to adapt to Pillow module. (  more [detials](http://stackoverflow.com/questions/19149643/error-in-images2gif-py-with-globalpalette)  




- Using main
- Adding path to python path to reduce calls. Do not replace but use append :
```
#fpath = os.path.join(os.path.dirname(__file__), 'utils')  
#sys.path.append(fpath)  
#print(sys.path)
``` 


- If we want to import a whole folder, use init -> in init cannot use relative path -> should be explicit -> this converts it into a package. We can also add modules from other dirs
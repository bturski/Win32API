
## Function name : AVIStreamStart
Group: Windows Multimedia - Library: avifil32    
***  


#### The AVIStreamStart function returns the starting sample number for the stream.
***  


## Code examples:
[Reading parameters of streams in AVI file](../../samples/sample_429.md)  

## Declaration:
```foxpro  
STDAPI_(LONG) AVIStreamStart(
  PAVISTREAM pavi
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER AVIStreamStart IN avifil32;
	INTEGER pavi  
```  
***  


## Parameters:
pavi
Handle to an open stream.
  
***  


## Return value:
Returns the number if successful or - 1 otherwise.   
***  

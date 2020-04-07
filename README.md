# GMS v179.4
MapleStory Localhost Project

Fork this project and replace the method on the specified line
https://github.com/RajanGrewal/Client176/blob/master/AuthHook/Client176/MapleHook.cpp#L4

## Values
```
void FuckMaple()
{
	Log(__FUNCTION__);

	//NGS Removal
	PatchRetZero(0x01E5B860);	

	//MSCRC Bypass
	PatchJmp(0x1EDBAB9, 0x1EDBB50);	
}
```

# vn-slicer
class for working with slices and collections

This class makes working with collections easier

The slice takes three parameters.
1st - Start position
2nd - End position
3th - Step

Slice can reverse collection: object[].Slice(-1(or other value), -1(or other value), -1(or other negative value)).

If you do not know any value, you can put -1.

Any collection can now be converted to a string easier: object[].ToStr(separator(default - "\n"))

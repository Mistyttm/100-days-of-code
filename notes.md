# Notes

### Day 19 4/11/21
**Notes:** 
  *  ``let`` allows for variables with the same name to exist within multiple functions
  *  ``const`` is not mutable
    *  ``const s = [1, 2, 3, 4]`` cannot be reassigned with ``s = [1, 2, 4]``
    *  ``s[1] = 45`` will however allow for that index to be mutated
  *  ``Object.freeze()`` is a function that completely stops objects from being altered.
    * If an editor is running in strict mode, an error will be thrown to the console
  *  Arrow notation allows for functions that are not going to be reused to be shortened down within a variable
    *  it allows for the ``return`` method to be skipped entirely
    *  eg: ``const i = () => "value";``
  *  

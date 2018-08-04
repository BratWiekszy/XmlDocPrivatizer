# XmlDocPrivatizer
Tool that removes private/internal documentation from .xml for .net assemblies.

### How it works
Apart legacy mode, it reads assembly the doc is for, and removes documentation entries for types/members that aren't public.

### Supported types of documentation:
- types
- properties (including indexers)
- fields
- constructors
- methods.
Method/constructor parameters may be generic closed types. Generic open types should generally work, although it's not guaranteed.

### Licence
Do whatever you like, excluding deriving financial benefits from this code in unmodifier form. 
It may be sold only if original code is less than 50%. 
Feel free to fork your own copy to extend functionality.

This patch comes from the flash-animations repository. It is identical with one exception: the stage size has already been entered as 780x515.

ClassAction questions don't use the NAAP-style dialog windows, so that part can be ignored.

Steps for patching a ClassAction question FLA:
- Open FLA to patch.
- Deal with font issues, if necessary.
- Save-as "-B".
- Copy and paste " Patch 2019-1" and " Stage Size" symbols to the library from "Patch 2019-CA.fla" (use C-C, C-V).
- Copy and paste combobox code -- not the symbol itself -- i.e. the text in the Actions window. The component is usually under "Template Stuff/Flash UI Components".
- Verify combobox code is replaced and patch objects are in library.
- Save, then publish.


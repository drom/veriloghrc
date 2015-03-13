Verilog highlighting scheme for Colorer

Installation instructions:

 * place verilog.hrc file wherever you want
 * modify your `\<colorer\>/hrc/proto.hrc` file in verilog section:

```xml
<prototype name="verilog" group="rare" description="Verilog HDL">
    <location link="rare/verilog.hrc"/>
    <filename weight='3'>/\.g?v$/i</filename>
</prototype>
```

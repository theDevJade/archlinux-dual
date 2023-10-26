# Oxe Reference

### Oxe is the assembly like language that is used to run code compiled from *Oxide*

## Data References

<tabs>
    <tab title="REGISTER">
        <table>
        <tr>
        <td><b>Data Int</b></td><td><b>Reference</b></td>
        </tr>
        <tr>
        <td>0</td><td>Register Command</td>
        </tr>
        <!---
        Sample Table Portion
        <tr>
        <td>0</td><td>Change</td>
        </tr>
        -->
        </table>
    </tab>
    <tab title="Other">
        WIP
    </tab>
</tabs>

## Example
```Shell
REGISTER 0 ["dumbo", "functionreference", "op"]

FUNC functionreference
DECLARE x PARAM_PLAYER
MESSAGE x "Wowee"
ENDFUNC
```


### This is NOT intended for manual editing, and is used for fast compilation and reference.

<seealso>
    <!--Provide links to related how-to guides, overviews, and tutorials.-->
</seealso>
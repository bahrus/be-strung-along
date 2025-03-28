# be-strung-along
Auto generate attributes via peer or ancestor elements

```html
<table>
    <tr id=testRow aria-rowindex=11
        xp-as
        xp-as-a-from=aria-rowindex
    >
        <td>
            <input type=radio-button be-strung-along="name:hello-a">
        </td>
    </tr>
</table>
```

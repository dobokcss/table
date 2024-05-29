# Table DobokCSS
- Border: `<table class="tb_border">`
- Hover: `<table class="tb_hover">`
- Striped: `<table class="tb_striped">`
- Fill: `<table class="tb_fill">`

## Basic structure
```HTML
<table>
    <thead>
        <tr>
            <th>#</th>
            <th>Name</th>
            <th>Occupation</th>
            <th>User</th>
         </tr>
     </thead>
     <tbody>
        <tr>
            <td colname="Id">1</td>
            <td colname="Name">Lorem</td>
            <td colname="Occupation">ipsum</td>
            <td colname="User">@dolor</td>
        </tr>
        <tr>
            <td colname="Id">2</td>
            <td colname="Name">Curabitur</td>
            <td colname="Occupation">dui</td>
            <td colname="User">@nunc</td>
        </tr>
    </tbody>
</table>
```

## Variables for the root CSS
To use `tb_prm, tb_scn, tb_hv_prm and tb_hv_scn`
creating the CSS Root with the following variables:

```CSS
:root {
    --prm: #40535b;
    --scn: #912e2e;
}
```

## Responsive table
- Use `<table class="tb_fluid">`
- See: [doc/README.md](doc/README.md)

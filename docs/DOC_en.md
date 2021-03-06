# Document

## m-select

### Description

**Attributes**

-   **disabled:** whether to disable components

**Styles**

-   **--m-select-color:** default color of select 
-   **--m-select-disable-color:** color of select when disabled
-   **--m-select-active-color:**  color of select when hovered
-   **--m-option-color:**  default color of option
-   **--m-option-active-color:**  color of option when actived
-   **--m-option-active-bg:**  background color of option when actived
-   **--m-option-disable-color:** color of option when disabled

**Values**

-   **disabled:** whether to disable components

**Methods**

-   **calcWidthAndPosition():** re-caculate component width and list position

**Events**

-   **change:** value changed



### Examples

```html
<m-select>
    <m-option value="1">option 1</m-option>
    <m-option value="2">option 2</m-option>
    <m-option value="3">option 3</m-option>
    <m-option value="4" selected>option 4</m-option>
    <m-option value="5" disabled>option 5</m-option>
    <m-option value="6">option 6</m-option>
    <m-option value="7">option 7</m-option>
    <m-option value="8">option 8</m-option>
</m-select>
```



### Preview

![Preview of select](../previews/preview_select.png)





## m-option

### Description

**Attributes**

-   **value:** options value (default value is options name)
-   **disabled:** whether to disable option
-   **selected:** whether to select option

**Styles**

-   none

**Values**

-   **value:** options value (default value is options name)
-   **disabled:** whether to disable option
-   **selected:** whether to select option

**Methods**

-   none



## m-input

### Description

**Attributes**

-   **value:** value of the input
-   **disabled:** whether to disable the input
-   **placeholder:** placeholder of the input
-   **type:** type of the input
-   **maxlength:** maxlength of the input

**Styles**

-   **--m-input-width：** width of the input
-   **--m-input-line-height：** line height of the input
-   **--m-input-color：** default color of the input
-   **--m-input-border-color：** defaulut boder color of the input
-   **--m-input-active-color：** color of input when focused
-   **--m-input-active-border-color：** border color of input when focused
-   **--m-input-disable-color：** color of input when disabled
-   **--m-input-disable-border-color：** border color of input when disabled

**Values**

-   **value：** value of the input
-   **placeholder：** placeholder of the input
-   **disabled：** whether to disable the input
-   **type：** type of the input
-   **maxlength：** maxlength of the input

**Methods**

-   none

**Events**

-   **focus:** input focused
-   **blur:** input blured
-   **change:** input value changed



### Examples

```html
<m-input type="text"></m-input>
<m-input type="text" disabled></m-input>
<m-input type="text" value="one company name"></m-input>
<m-input type="text" value="one company name" disabled></m-input>
<m-input type="text" value="one company name"></m-input>
```



### preview

![Preview of input](../previews/preview_input.png)



## m-switch

### Description

**Attributes**

-   **value:** current state of switch
-   **disabled:** whether to disable the switch
-   **selected:** active the switch

**Styles**

-   none

**Values**

-   **value：** set the state of the switch
-   **disabled：** whether to disable the switch

**Methods**

-   none

**Events**

-   **change:** value changed



### Examples

```html
<m-switch disabled></m-switch>
<m-switch></m-switch>
<m-switch selected></m-switch>
```



### preview

![Preview of switch](../previews/preview_switch.png)



## m-slider

### Description

**Attributes**

- **value:** current value of slider
- **min:** min value of slider
- **max:** max value of slider
- **size:** size of component (min)
- **disabled:** whether to disable the switch
- **show-input:** whether to show input

**Styles**

- **--m-slider-main-color:** main color
- **--m-slider-auxiliary-color:** auxiliary color

**Values**

- **value:** set or get value of slider
- **disabled:** set or get whether to disable the slider

**Methods**

- none

**Events**

- none



### Examples

```html
<m-slider min="0" max="20" value="0"></m-slider>
<m-slider min="0" max="20" value="10"></m-slider>
<m-slider min="0" max="20" value="10" disabled></m-slider>
<m-slider min="0" max="20" value="10" show-input></m-slider>
<m-slider min="0" max="20" value="10" show-input disabled></m-slider>
```

**preview**

![Preview of slider](../previews/preview_slider.png)



## m-range-slider

### Description

**Attributes**

- **left:** current left value of slider
- **right:** current right value of slider
- **min:** min value of slider
- **max:** max value of slider
- **size:** size of component (min)
- **disabled:** whether to disable the switch
- **show-input:** whether to show input

**Styles**

- **--m-slider-main-color:** main color
- **--m-slider-auxiliary-color:** auxiliary color

**Values**

- **value:** set or get range of slider
- **disabled:** set or get whether to disable the slider

**Methods**

- none

**Events**

- none



### Examples

```html
<m-range-slider min="0" max="20" left="0" right="20"></m-range-slider>
<m-range-slider min="0" max="20" left="8" right="15"></m-range-slider>
<m-range-slider min="0" max="20" left="8" right="15" disabled></m-range-slider>
<m-range-slider min="0" max="20" left="8" right="15" show-input></m-range-slider>
<m-range-slider min="0" max="20" left="8" right="15" show-input disabled></m-range-slider>
```



### preview

![Preview of range-slider](../previews/preview_range_slider.png)



## m-album

### Description

**Attributes**

- **autoplay:** whether to auto play album
- **interval:** time of auto play interval, 3000ms default
- **trigger:** way to trigger the indicator, click or hover
- **indicator-position:** position of indicators, outside or inside

**Styles**

- none

**Values**

- none

**Methods**

- none

**Events**

- none



### Examples

```html
<m-album>
    <m-album-item>
        <h3>1</h3>
    </m-album-item>
    <m-album-item>
        <h3>2</h3>
    </m-album-item>
    <m-album-item>
        <h3>3</h3>
    </m-album-item>
    <m-album-item>
        <h3>4</h3>
    </m-album-item>
</m-album>
```

**预览**

![Preview of album](../previews/preview_album.png)



## m-operation-list

### Description

**Attributes**

-   **disabled:** whether to disabled components

**Styles**

-   **--m-operation-list-color:** default color of operation list
-   **--m-operation-list-bg:** default background color of operation list
-   **--m-operation-list-disable-color:** color of operation list when disabled
-   **--m-operation-list-disable-bg:** background color of operation list when disabled
-   **--m-operation-color:** default color of operaion
-   **--m-operation-active-color:** color of operation when actived
-   **--m-operation-active-bg:** background color of operation when actived
-   **--m-operation-disable-color:** color of operation when disabled

**Values**

-   **disabled:** whether to disabled components

**Methods**

-   **calcWidthAndPosition():** re-caculate component width and list position



### Examples

```html
<m-operation-list>
    <m-operation operation="helloWorld">edit</m-operation>
    <m-operation operation="helloWorld" disabled>compare</m-operation>
    <m-operation>delete</m-operation>
    <m-operation>more detail</m-operation>
</m-operation-list>
```



### preview

![Preview of operation-list](../previews/preview_operation_list.png)



## m-operation

### Description

**Attributes**

-   **operation:** function called when clicked
-   **disabled:** whether to disabled this operation

**Styles**

-   none

**Values**

-   **operation:** function called when clicked
-   **disabled:** whether to disabled this operation

**Methods**

-   none



## m-function

### Description

**Attributes**

-   **icon:** unicode of icon
-   **icon-class:** class of icon
-   **disabled:** whether to disabled this function
-   **operation:** function called when clicked
-   **tip:** tip showed when hover component

**Styles**

-   **--m-function-color:** default color of components
-   **--m-function-bg:** default background color of components
-   **--m-function-disable-color:** color of components when disabled
-   **--m-function-disable-bg:** background color of components when disabled

**Values**

-   **icon:** unicode of icon
-   **icon-class:** class of icon
-   **disabled:** whether to disabled this function
-   **operation:** function called when clicked
-   **tip:** tip showed when hover component

**Methods**

-   none



### Examples

```html
<m-function icon-class="ming-icon-plus" tip="upload image"></m-function>
```



### preview

![Preview of function](../previews/preview_function.png)



## m-icon-function

### Description

**Attributes**

-   **icon:** unicode of icon
-   **icon-class:** class of icon
-   **disabled:** whether to disabled this function
-   **operation:** function called when clicked
-   **tip:** tip showed when hover component

**Styles**

-   **--m-icon-function-color:** default color of components
-   **--m-icon-function-active-color:** color of components when actived
-   **--m-icon-function-active-bg:** background color of components when actived
-   **--m-icon-function-disable-color:** color of components when disabled
-   **--m-icon-function-tip-color:** default color of tip
-   **--m-icon-function-tip-bg:** default background color of tip

**Values**

-   **icon:** unicode of icon
-   **icon-class:** class of icon
-   **disabled:** whether to disabled this function
-   **operation:** function called when clicked
-   **tip:** tip showed when hover component

**Methods**

-   none



### Examples

```html
<m-icon-function icon-class="ming-icon-home" tip="Home" operation="helloWorld"></m-icon-function>
```



### preview

![Preview of icon-function](../previews/preview_icon_function.png)



## m-menu

### Description

**Attributes**

-   **menu-target:** route target when menu clicked

**Styles**

-   none

**Values**

-   **menu-target:** route target when menu clicked

**Methods**

-   none

**Events**

-   **change:** menu changed



### Examples

```html
<m-menu menu-target="main-content">
    <m-menu-group icon="ming-icon-settings" group-name="group 1">
        <m-menu-item menu-route="">item 1</m-menu-item>
        <m-menu-item menu-route="">item 2</m-menu-item>
    </m-menu-group>
    <m-menu-group icon="ming-icon-settings" group-name="group 2">
        <m-menu-item menu-route="">item 1</m-menu-item>
        <m-menu-item menu-route="">item 2</m-menu-item>
        <m-menu-item menu-route="">item 3</m-menu-item>
        <m-menu-item menu-route="">item 4</m-menu-item>
    </m-menu-group>
    <m-menu-group icon="ming-icon-settings" group-name="group 3">
        <m-menu-item menu-route="">item 1</m-menu-item>
        <m-menu-item menu-route="">item 2</m-menu-item>
    </m-menu-group>
    <m-menu-group icon="ming-icon-settings" group-name="group 4" menu-route=""></m-menu-group>
    <m-menu-group icon="ming-icon-settings" group-name="group 5">
        <m-menu-item menu-route="">item 1</m-menu-item>
        <m-menu-item menu-route="">item 2</m-menu-item>
    </m-menu-group>
    <m-menu-group icon="ming-icon-settings" group-name="group 6">
        <m-menu-item menu-route="">item 1</m-menu-item>
        <m-menu-item menu-route="">item 2</m-menu-item>
        <m-menu-item menu-route="">item 3</m-menu-item>
    </m-menu-group>
    <m-menu-group icon="ming-icon-settings" group-name="disabled group" disabled>
        <m-menu-item menu-route="">item 1</m-menu-item>
        <m-menu-item menu-route="">item 2</m-menu-item>
    </m-menu-group>
    <m-menu-group icon="ming-icon-settings" group-name="group 8">
        <m-menu-item menu-route="" disabled>disabled item</m-menu-item>
        <m-menu-item menu-route="">item 2</m-menu-item>
    </m-menu-group>
</m-menu>
```



### preview

![Preview of menu](../previews/preview_menu.png)



## m-menu-group

### Description

**Attributes**

-   **icon:** icon for menu group
-   **group-name:** first level menu name
-   **menu-route:** url of menu
-   **disabled:** whether to disable this menu group

**Styles**

-   **--m-menu-group-active-bg:**  background color of first level menu when actived
-   **--m-menu-group-color:** default color of first level menu
-   **--m-menu-group-disable-color:** color of first level menu when disabled
-   **--m-menu-group-icon-active-color:** color of menu icon when actived
-   **--m-menu-group-active-color:** color of menu name when actived
-   **--m-menu-group-icon-disable-color:** color of menu icon when disabled
-   **--m-menu-item-color:** default color of second level menu
-   **--m-menu-item-active-color:** color of second level menu when actived
-   **--m-menu-item-disable-color:** color of second level menu when disabled

**Values**

-   **icon:** icon for menu group
-   **group-name:** first level menu name
-   **menu-route:** url of menu
-   **disabled:** whether to disable this menu group

**Methods**

-   none





## m-menu-item

### Description

**Attributes**

-   **menu-route:** url of menu
-   **disabled:** whether to disable this menu

**Styles**

-   none

**Values**

-   **menuRoute:** url of menu
-   **disabled:** whether to disable this menu

**Operation**

-   none





## m-table/m-simple-table

### Description

**Attributes**

-   none

**Styles**

-   **--m-table-header-bg：** background of table header 

**Values**

-   **config:** get table config

**Methods**

-   **register(config) :** config this component
-   **render():** re-render this table
-   **destroy():** destroy this table
-   **showError():** show table error page
-   **hideError():** hide table error page
-   **showEmpty():** show table empty page
-   **hideEmpty():** hide table empty page



### Examples

```html
<style type="text/css">
	.main-table {
        height: 600px;
    }
</style>

<m-table class="main-table" id="main-table"></m-table>

<script type="text/javascript">
	let config = {
        pageSize: 20,
        data: async function () {
            let tabledata = {
                status: 0,
                data: [],
                total: 0,
            };
            await fly.get('/data/table_example.json')
                .then(function (response) {
                    if (response.status == 200) {
                        tabledata.status = response.status;
                        if (response.data.status == 200) {
                            tabledata.data = response.data.data;
                            tabledata.total = response.data.total;
                        }
                    }
                });
            return tabledata;
        },
        columns: [
            [
                {
                    title: 'col1-1',
                    rowspan: 2,
                    formatter: function (column, row, index) {
                        return index + 1;
                    }
                },
                {title: 'col1-2', colspan: 9},
                {title: 'col1-3', colspan: 3},
                {
                    title: 'col1-4',
                    fixed: true,
                    rowspan: 2,
                    formatter: function (column, row, index) {
                        return `<m-operation-list>
                            <m-operation>operation A</m-operation>
                            <m-operation>operation B</m-operation>
                            <m-operation>operation C</m-operation>
                        </m-operation-list>`;
                    }
                },
            ],
            [
                {title: 'col2-2', field: 'col1'},
                {title: 'col2-3', field: 'col2'},
                {title: 'col2-4', field: 'col3'},
                {title: 'col2-5', field: 'col4'},
                {title: 'col2-6', field: 'col5'},
                {title: 'col2-7', field: 'col6'},
                {title: 'col2-8', field: 'col7'},
                {title: 'col2-9', field: 'col8'},
                {title: 'col2-10', field: 'col9'},
                {title: 'col2-11', field: 'col10'},
                {title: 'col2-12', field: 'col11'},
                {title: 'col2-13', field: 'col12'},
            ]
        ]
    };

    document.querySelector('#main-table').register(config);
</script>
```



### Preview

![Preview of table](../previews/preview_table.png)



## m-form-item

### Description

**Attributes**

-   none

**Styles**

-   **--m-form-item-color：** default color of label
-   **--m-form-item-active-color：** color of label when focused

**Values**

-   none

**Methods**

-   none



### Examples

```html
<m-form-item name="company name">
    <m-input type="text" disabled></m-input>
</m-form-item>
<m-form-item name="company name">
    <m-input type="text"></m-input>
</m-form-item>
<m-form-item name="company name">
    <m-input type="text"></m-input>
</m-form-item>
<m-form-item name="company name">
    <m-input type="text" value="the name of company"></m-input>
</m-form-item>
<m-form-item name="company name">
    <m-select>
        <m-option value="1">option 1</m-option>
        <m-option value="2">option 2</m-option>
        <m-option value="3">option 3</m-option>
        <m-option value="4" selected>option 4</m-option>
        <m-option value="5" disabled>option 5</m-option>
        <m-option value="6">option 6</m-option>
        <m-option value="7">option 7</m-option>
        <m-option value="8">option 8</m-option>
    </m-select>
</m-form-item>
```

**preview**

![Preview of form-item](../previews/preview_form_item.png)



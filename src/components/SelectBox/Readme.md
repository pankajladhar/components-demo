<!--- Sample with out markdown -->

Sample SelectBox
```js
    const selectBoxProps = {
        debug: false,
        options: [
            { 
                value: "AMEX", 
                title: "American Express",
                iconInfo: {
                    "icon" : "amex-icon",
                    "alignment" : "right"
                }
            },
            {   value: "DELTA",
                title: "Visa Debit/Electron",
                iconInfo: {
                    "icon" : "visa-icon",
                    "alignment" : "right"
                }
            },
            {   value: "DINERS",
                title: "Diners Club",
                iconInfo: {
                    "icon" : "diners-icon",
                    "alignment" : "right"
                }
            },
            {   value: "MC",
                title: "MasterCard Credit",
                iconInfo: {
                    "icon" : "mastercard-icon",
                    "alignment" : "right"
                }
            },
            {   value: "MCDEBIT",
                title: "MasterCard Debit",
                iconInfo: {
                    "icon" : "mastercard-icon",
                    "alignment" : "right"
                }
            },
            {   value: "SWITCH",
                title: "Maestro",
                iconInfo: {
                    "icon" : "maestro-icon",
                    "alignment" : "right"
                }
             },
            { 
                value: "VISA",
                title: "Visa Credit",
                iconInfo: {
                    "icon" : "visa-icon",
                    "alignment" : "right"
                }
            },
        ],
        onChange:(value)=>{console.log(value)}
    };
    <SelectBox {...selectBoxProps}/>
```




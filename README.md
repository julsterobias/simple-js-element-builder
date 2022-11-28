# simple-js-element-builder
Simple js element builder


#Usage:

General Elements
var el = js_el_generator(
    {
        type: 'div',
        text: 'Blah blah blah',
        attributes: [
            {
                attr: 'class',
                value: 'my-class'
            },
            {
                attr: 'id',
                value: 'my-id'
            },
            {
                attr: 'data-flag',
                value: true
            }
        ]
    }
)

#Select
var el = js_el_generator(
    {
        type: 'select',
        attributes: [
            {
                attr: 'class',
                value: 'my-class'
            },
            {
                attr: 'id',
                value: 'my-id'
            },
            {
                attr: 'data-flag',
                value: true
            }
        ],
        options: [
            {
                text: 'Option 1',
                value: 'option-1'
            },
            {
                text: 'Option 2',
                value: 'option-2
            }
        ],
        value: 'option-2'
    }
)
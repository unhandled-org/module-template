## un-nm-template (semver. X.X.X XXX-ready)


### What problem does it solve?

This is the portion of the README where you thoroughly describe what the intents of this module are and what problems it is meant to solve.
Try to keep the description structured and clear as the reader may not initially know why this module exists.

This is also the portion where a summary should be written to in a stateful manner describe the overall purpose of this module.

| Lib           | Support       | Ready |
| ------------- |:-------------:| -----:|
| All methods   | All methods   | Yes   |

| Lib           | Support       | Ready |
| ------------- |:-------------:| -----:|
| All methods   | All methods   | Yes   |

| Lib           | Support       | Ready |
| ------------- |:-------------:| -----:|
| All methods   | All methods   | Yes   |

| Lib           | Support       | Ready |
| ------------- |:-------------:| -----:|
| All methods   | All methods   | Yes   |


### What does this module do?

In a summary describe what the actual functionality of the module is and how the implementation solves the above mentioned problem. Describe how this implementation affects its usability.

- This is a major feature of the module
- This is another major feature of the module



### What does it support?

This is where you describe what libraries / frameworks that this module supports, list them below.

- Example [Read docs](https://github.com/example/example)
- Example [Read docs](https://github.com/example/example)
- Example [Read docs](https://github.com/example/example)
- Example [Read docs](https://github.com/example/example)

Or any additional links



### How do I use it?

There are some local scripts to help with your development

##### Tests
This will run the tests stored in `test/index.js` see the file for more information.

```javascript
npm run-script test
```

##### Examples
This will run the examples file `example.js` see the file source for examples using this module.

```javascript
npm run-script example
```


Simply require the module in your file using the convention


```javascript
const numberFactory = require('@unhandled/un-nm-number-factory');
const number = numberFactory(
    {
        handler: 'float',
        config: {
            start: 0,
            end: 1000,
            options: { decimals: 8}
        }
    }
);

number().create({}).then(() => ..);
```


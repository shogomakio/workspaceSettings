# PHP Mess Detector

## Rules

for information about the rules refer to: [https://phpmd.org/rules/]

## How to add rules

In the *MessDetector.xml* file, inside the `ruleset` scope, add a `rule` tag with reference of the rule you want to add and their respective values.

e.g.:

```xml
    <rule ref="rulesets/cleancode.xml">
        <exclude name="ElseExpression" />
        <exclude name="StaticAccess" />
    </rule>
```

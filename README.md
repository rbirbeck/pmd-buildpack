# Buildpack to add PMD to Heroku CI

Sample project implementation here: https://github.com/rbirbeck/DF19

## Example

```json
{
    ...,
    "environments": {
        "test": {
            "scripts": {
                "test": "./pmd-bin-6.19.0/bin/run.sh pmd -d ./force-app/main -R rulesets/java/quickstart.xml -f text"
            },
        }
}
```

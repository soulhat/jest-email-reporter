<div align="center">
  <img height="200"
    src="">
  <h1>jest-email-reporter</h1>
  <p>See jest test errors on e-mail</p>
</div>

## Install

```sh
npm install --save-dev jest-email-reporter
# or
yarn add -D jest-email-reporter
```

## Usage

You must configure the jest config. Do not forget `from` and `to` e-mail addresses.

```javascript
{
    reporters: [
        "default",
        ["@tglink/jest-email-reporter", {
            from: 'from@example.com',
            to: 'to@example.com',
            subject: 'Optional subject', // optional
        }]
    ]
}
```

## Result

![Result image](./src/result.png)

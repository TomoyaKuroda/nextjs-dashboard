Email: user@nextmail.com
Password: 123456

`openssl rand -base64 32`
node -e "console.log(require('crypto').randomBytes(32).toString('base64'))"
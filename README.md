# fake-users-9
## to install
```
npm install fake-users-9
```

### A simple use of Fake Users

```javascript
var fake = require('fake');
fake.addUser('Caio', 'Sempronio');
fake.addUser('Orazio', 'Caligola');
fake.deleteUser(1);
fake.findUserByName('Caio');
fake.findUserById(0);
fake.reset();
```

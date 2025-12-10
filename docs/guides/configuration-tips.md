---
title: 4 oldal
sidebar_position: 4
---

### 2. configuration-tips.md

```markdown
# Configuration Tips

## Basic Configuration

To configure your application, open the `config.js` file and update the following settings:

```javascript
module.exports = {
  app: {
    port: 3000,
    env: 'development'
  },
  db: {
    host: 'localhost',
    port: 5432,
    username: 'user',
    password: 'password'
  }
};

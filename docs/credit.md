# credit

A credit represents value that will be used up before further charges are assigned to an account.

## Actions

### `create`

`heroku.account().credits().create({attributes}, {callback});`

Method | Path
--- | ---
POST | /account/credits

### `info`

`heroku.account().credits({credit_id}).info({callback});`

Method | Path
--- | ---
GET | /account/credits/{credit_id}

### `list`

`heroku.account().credits().list({callback});`

Method | Path
--- | ---
GET | /account/credits


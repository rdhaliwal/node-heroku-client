# addon

Add-ons represent add-ons that have been provisioned and attached to one or more apps.

## Actions

### `create`

`heroku.apps({app_id_or_name}).addons().create({attributes}, {callback});`

Method | Path
--- | ---
POST | /apps/{app_id_or_name}/addons

### `delete`

`heroku.apps({app_id_or_name}).addons({addon_id_or_name}).delete({callback});`

Method | Path
--- | ---
DELETE | /apps/{app_id_or_name}/addons/{addon_id_or_name}

### `info`

`heroku.apps({app_id_or_name}).addons({addon_id_or_name}).info({callback});`

Method | Path
--- | ---
GET | /apps/{app_id_or_name}/addons/{addon_id_or_name}

### `list`

`heroku.addons().list({callback});`

Method | Path
--- | ---
GET | /addons

### `info`

`heroku.addons({addon_id_or_name}).info({callback});`

Method | Path
--- | ---
GET | /addons/{addon_id_or_name}

### `listByApp`

`heroku.apps({app_id_or_name}).addons().listByApp({callback});`

Method | Path
--- | ---
GET | /apps/{app_id_or_name}/addons

### `update`

`heroku.apps({app_id_or_name}).addons({addon_id_or_name}).update({attributes}, {callback});`

Method | Path
--- | ---
PATCH | /apps/{app_id_or_name}/addons/{addon_id_or_name}


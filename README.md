# Cutover Plan
## Phase 1 - Planning and Documenting
The current server must have all of its roles, channels, and categories documented. This includes a matrix of what permissions are 
assigned to what roles, and how category/channel permissions are set to allow/disallow actions independent of roles. Additionally,
Sapphire bot is currently used to handle some automation; these processes must also be documented.

### To do:
  - ~~Document roles~~
  - ~~Document channels~~
  - ~~Document Sapphire Bot setup~~
  - ~~Build roles permissions matrix~~
  - Build channel permissions matrix

## Phase 2 - Role Changes
During this phase, the roles will be amended to ensure each one has the correct permissions for the categories they should be able to view/edit.
There will be a core set of structural roles, plus additional vanity roles. Server bots (apart from Sapphire) have their own role.

### To do:
  - ~~Build Roles tree~~
  - Modify Role permissions as required
  - Trim excess Roles as required

## Phase 3 - Channel Changes
During this phase, the channels will be sorted into their respective categories. All channels will need to inherit their permissions from the
category they are placed into, and each category will need to have their permissions set correctly based on the roles able to access them.

### To do:
  - ~~Build Channels/Categories tree~~
  - Create Categories
  - Move existing Channels to their respective Category as required
  - Add Channels to Categories as required
  - Review Channel permissions to ensure they are inherited from their Category
  - Trim excess Channels as required

## Phase 4 - Onboarding Changes
This is probably the most complex change, as it requires the modification of Sapphire bot behaviour.

### To do:
  - Set up Rules for onboarding within the server itself
  - Add Role assignment to Sapphire for new entrants
  - Remove Sapphire's rules section (covered by the onboarding)

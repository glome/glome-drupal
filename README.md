Glome OAuth2 Connector.

Required parameters:
Token endpoint http://glome_oauth2_middleware/app.php/oauth/v2/token
Client id
Client secret

## Usage

Enable the Feature Glome OAuth2 Connector 
Configure the module with Glome OAuth2 parameters. admin/config/services/oauth2-authentication
The module exposes Drupal block Login with Glome.
Move to preferred place in Structure->Blocks eg. Left Sidebar
Logout.
Sidebar should now allow you to login with Glome, via a button.
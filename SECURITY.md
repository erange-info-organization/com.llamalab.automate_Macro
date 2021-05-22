Security
Privileges
Android control access to its features in multiple ways, in Automate they’re all generalized as the term “privileges”.

Most common access control in Android is a “permission”. On Android 6+ a permission is granted by the user at run-time, usually prior to use. On lower Android versions, all permissions requested by an app are undeniably granted at installation. Automate use a hybrid solution where a few add-ons apps request a subset of related permissions each. Prior to Android 6 the add-ons are used to give the user a choice to only grant a subset of permissions, and since Android 6 where available run-time permissions are deficient, e.g. for internet and superuser/root access, and to work around bugs (Modify private settings) and Android 9+ feature restrictions. In either case, permissions are managed and enforced by the system.

Other kinds of access controls are spread throughout system settings, there’s options to enable the Accessibility service, Device Administrator, and other “Special app access” like Usage access, Modify system settings, etc..

Automate can be granted or denied privilege by clicking the check mark buttons in the Privileges section on flow details screen, in Privileges settings, or where appropriate in system settings.

Even irrevocable privileges (grayed out check mark) are listed so users are able to see them being used by a flow.

Accounts
When authorization is required, Automate will never force a user to write a username or password within a flow. Instead the credentials are stored in accounts handled by the Android operating system. Accounts are then only referenced by their public names, making flows safe to share among users.

Generic credentials
A username and password are often required when accessing FTP/SMTP servers or personal web content. Automate has its own type of account for those cases, the “generic credentials” account. Add or remove “generic credentials” in system Account settings.

Google account
Automate can never access the password of a Google account. Instead, Automate requests an authentication token when accessing online services like Gmail and Google Drive. This token isn’t accessible by, nor stored in a flow.

Online services
All communication with online services requiring authorization are done though secure (HTTPS) connections, this includes the following features:

Automate cloud messaging
Automate community
Gmail
Google Drive

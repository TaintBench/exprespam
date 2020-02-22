# PROFILE
# Installation:
![ICON](icon.png)
# General Information:
- **fileName**: exprespam.apk
- **packageName**: frhfsd.siksdk.ujdsfjkfsd
- **targetSdk**: 8
- **minSdk**: 8
- **maxSdk**: undefined
- **mainActivity**: .WrehifsdkjsActivity
# Behavior Information:
## Activities:
- WrehifsdkjsActivity sends phone numbers and contacts to a remote server. 
# Detail Information:
## Activities: 1
	.WrehifsdkjsActivity
## Permissions: 4
	android.permission.READ_CONTACTS
	android.permission.GET_ACCOUNTS
	android.permission.INTERNET
	android.permission.READ_PHONE_STATE
## Sources: 2
	<android.telephony.TelephonyManager: java.lang.String getLine1Number()>: 1
	<org.json.JSONObject: int getInt(java.lang.String)>: 1
## Sinks: 4
	<android.app.ProgressDialog: void setMessage(java.lang.CharSequence)>: 1
	<android.app.Activity: void onCreate(android.os.Bundle)>: 1
	<android.os.Handler: boolean sendMessage(android.os.Message)>: 7
	<android.app.ProgressDialog: void setProgressStyle(int)>: 1

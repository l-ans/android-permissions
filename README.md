## Android permissions

The repository contains all Android permissions in a JSON-file.

The format is:

```
{ "permissions" :
  [
    {
      "name": "PERMISSION_NAME",
      "constant_value" : "android.permission,PERMISSION_NAME",
      "protection-level": "normal"
    },
    {
      ...
    }
  ]
}
```

The data was taken from https://developer.android.com/reference/android/Manifest.permission

```
python -m pip install --index-url [https://.....] -e .[full]

```

| Command Part	|  What it Does  |
|-----|-----|
|python -m pip install	|The standard command to start the Python package installation process.|
|--index-url ...	|Specifies a custom server address to search for and download required package dependencies. In this case, it's pointing to Zebra's internal development package repository.|
|-e .	|Editable Mode: This is the key part. Instead of copying the files to a system folder, it creates a link to your project's source code in the current directory (.). This means any changes you make to the code are immediately active in your Python environment without needing to reinstall.|
|[full]	|Extras: This installs optional features or dependencies. The project defines a [full] category that includes all extra packages needed for complete functionality, which might not be required for a basic installation.|



E.g:</br>
```
python -m pip install --index-url https://evtpypi.company_xyz.com/evt/development -e .[full]

```

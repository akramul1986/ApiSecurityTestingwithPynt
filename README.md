# ApiSecurityTestingwithPynt
Api Security Testing Via Pynt
Install Pynt CLI: python -m pip install pyntcli
Ensure Docker engine is available and running on your machine.
Ensure your functional test collection is available in your workspace.
If your functional tests requires environment variables, make sure they are set.
Make sure your target is up.

Usage: pynt newman [OPTIONS] 
Options:
--collection - Postman collection file name
--environment - Postman environment file name
--reporters - output results to pynt_results.json and pynt_results.html

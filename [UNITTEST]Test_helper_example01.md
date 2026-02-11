Syntax:</BR>
```
python -c "from [file_path] import [function_name]; [parameter_name] = [value]; print(f'Input: {[parameter_name]} -> Result: {[helper_function]([parameter_name])}')"
```

Example:</BR>
|Component	| Example from Command| Description|
|-----|-----|-----|
|Module Path	|atf.dut._zt4_sentinel|	This is the full path to the Python module (file) from which a function is being imported.|
|Function Name |_no_printline_coupler|	This is the specific function (helper) being imported from the module and executed.|
|Variable|	pcc|	This is the variable that holds the input data for the function.|
|Value|'ZT41143-T010000Z'|	This is the actual data assigned to the parameter variable.|
```
python -c "from atf.dut._zt4_sentinel import _no_printline_coupler; pcc = 'ZT41143-T010000Z'; print(f'Input: {pcc} -> Result: {_no_printline_coupler(pcc)}')"
```

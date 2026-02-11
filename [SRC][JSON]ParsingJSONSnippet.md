import json </br>

json_data = '''{ ... }'''
data = json.loads(json_data)</br>
print(data)</br>
print(data[json_parameter])</br>


Example: </br>
```
import json

json_data = '''{
    "name": "Mos",
    "age": 41,
    "city":"Singapore Central",
    "weapons":["bo staff", "sword","dagger"]
}'''


data = json.loads(json_data)
print(data)
print(data['name'])
print(data['age'])
print(data['city'])
print(data['weapons'])
```

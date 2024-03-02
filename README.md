# сделать словарь из названий городов
# сделать словарь из названий городов  в виде "name": "Ясный"
city_dict = {city['name']: city['population'] for city in cities}
print(city_dict)

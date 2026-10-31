# alu-back-end

Python scripts that use the JSONPlaceholder REST API
(https://jsonplaceholder.typicode.com) to gather employee TODO data and
export it to CSV and JSON.

## api/

| File | Description |
|------|-------------|
| `0-gather_data_from_an_API.py` | Prints an employee's TODO progress |
| `1-export_to_CSV.py` | Exports an employee's tasks to `USER_ID.csv` |
| `2-export_to_JSON.py` | Exports an employee's tasks to `USER_ID.json` |
| `3-dictionary_of_list_of_dictionaries.py` | Exports all employees' tasks to `todo_all_employees.json` |

Requires `python3` and the `requests` module.

### iTop extension: Unique inventory number

#### English:
We use the "Asset number" field for generating and storing inventory numbers (EAN-13) for physical devices.
- The `asset_number` field cannot be empty.
- The `asset_number` field must be unique.
- Editing the `asset_number` field is prohibited.
- When creating an physical object, the `asset_number` field is hidden.
- When creating an physical object we generate an EAN-13 based on the object `id` and write it to the `asset_number` field.

#### Русский:
Используем поле "Номер актива" для генерации и хранения инвентарных номеров (EAN-13) для физических устройств.
- Поле `asset_number` не может быть пустым.
- Поле `asset_number` должно быть уникальным.
- Редактирование поля `asset_number` запрещено.
- При создании объекта поле `asset_number` скрыто.
- При создании объекта генерируем EAN-13 на основании `id` и записываем в поле `asset_number`.
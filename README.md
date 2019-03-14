# add-role

```php
// Добавление роли WP
$result = add_role( 'user_role', 'Пользователь',
   array(
     'user-role' => true, // пользователь
   )
 );

// Удаление роли WP
function wps_remove_role() {
  remove_role( 'editor' ); // реадактор
  remove_role( 'author' ); // автор
  remove_role( 'contributor' ); // участник
  remove_role( 'subscriber' ); // подписчик
}
add_action( 'init', 'wps_remove_role' );
```

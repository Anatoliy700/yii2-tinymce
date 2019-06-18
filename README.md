# TinyMCE v5 Расширение для Yii2

TinyMCE - WYSIWYG редактор для встраивания в веб-страницы.

## Установка

Устанвливается через [Composer](http://getcomposer.org/download/) 

`php composer.phar require --prefer-dist anatoliy700/yii2-tinymce "*"`

или добавить 

`anatoliy700/yii2-tinymce: "*"`

в разделе `require` вашего composer.json файла.

## Использование

```php
use anatoliy700\tinymce\TinymceWidget;

echo $form->field($model, 'attrebuteName')->widget(TinymceWidget::className(), [
    'editorConfig' => [
        //конфигурация редактора(подробнее в офицальной документации, ссылки ниже)
    ]
])
```

## Полезные ссылки

TinyMCE Configuration options reference - <https://www.tiny.cloud/docs/configure/>

TinyMCE API Reference - <https://www.tiny.cloud/docs/api/>

Храните свои глобальные файлы медиа в папке `assets/`. Файлы группируются по типу для удобного поиска. Если один файл имеет категорию использования, то он помещается в свою подпапку. 

Важно! Любой файл, который помещен в `assets/`, либо используется, либо будет использоватся в проєкте больше 1 раза. Иначе, файл должен находиться в папке модуля? который его использует. 

> Это сделанно для того, что бы разграничить глобальные файлы и отделить их от модулей, чтобы модули можно было безболезненно копировать и переносить от всего проекта. 
> 
> Если файл находится в папке `assets/`, то это означает: обязательно, при его удалении, следует проверить зависимости.

[Пример](#example) файловой струкутры

---

Store your global media files in the `assets/` folder. Files are grouped by type for easy searching. If one file has a specific category of use, it is placed in its own subfolder.

Important! Any file that is placed in `assets/` is either used or will be used more than once in the project. Otherwise, the file must be in the folder of the specific module that uses it.

> This is done to differentiate global files and separate them from modules, so that modules can be painlessly copied and moved from the entire project.
>
> If the file is in the `assets/` folder, this means that, when deleting it, it is imperative to check the dependencies.

[Example](#example) of the file structure

<a name="example"></a>
```
# assets/
## audio/
### main_menu.ogg

```
# MSBuild

***\*.props** обычно отвечают за свойства проекта и переменные окружения. **\*.targets** отвечают за сборку — в них описывается, что делать с файлами(а может и не с файлами), которые добавлены к проекту, т.е. все возможные действия/задания(Tasks) и за типы файлов проекта определямые схемой(ProjectSchema) и правилами(Rules).*

- **Основные настройки компилятора**

    1. https://learn.microsoft.com/ru-ru/dotnet/csharp/language-reference/compiler-options/

- **Условные конструкции при настройке компилятора**

    - https://learn.microsoft.com/ru-ru/visualstudio/msbuild/msbuild-conditional-constructs?view=vs-2022
    - https://learn.microsoft.com/ru-ru/visualstudio/msbuild/msbuild-conditions?view=vs-2022

- **Настройка компилятора в файле *csproj***

    - https://learn.microsoft.com/ru-ru/dotnet/core/project-sdk/msbuild-props

- **Настройка компилятора в файле *\*.props***

    - https://habr.com/ru/articles/448216/#lvl1_props
    - https://learn.microsoft.com/ru-ru/visualstudio/msbuild/customize-your-build?view=vs-2022
    - https://skjoldrun.github.io/docs/csharp/project-props-targets.html

- **Настройка компилятора в файле *\*.targets***

    - https://habr.com/ru/articles/448216/#lvl2_targets
    - https://learn.microsoft.com/ru-ru/visualstudio/msbuild/customize-your-build?view=vs-2022
    - https://skjoldrun.github.io/docs/csharp/project-props-targets.html

- **Работа с менеджером пакетов *Nuget***

    - https://learn.microsoft.com/ru-ru/nuget/quickstart/install-and-use-a-package-in-visual-studio

- **Использование и настройка пакетов в файле *csproj***

    - https://learn.microsoft.com/ru-ru/nuget/consume-packages/package-references-in-project-files

- **Использование и настройка пакетов в файле *\*.props***

    - https://learn.microsoft.com/ru-ru/nuget/consume-packages/central-package-management

- **Работа с утилитой *dotnet***

    - https://learn.microsoft.com/ru-ru/nuget/consume-packages/central-package-management

- **Интеграция скриптовых действий в компиляторе при сборке**

    - https://learn.microsoft.com/en-us/aspnet/web-forms/overview/deployment/advanced-enterprise-web-deployment/running-windows-powershell-scripts-from-msbuild-project-files

# Clang и Cmake


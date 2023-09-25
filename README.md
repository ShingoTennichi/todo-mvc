# First ASP.NET MVC Practice(https://github.com/cappuccinocodes/c-sharp-academy-mvc-01-todo-vsc/tree/master)

```sh
# create ASP.NET project
dotnet new mvc --name Todo
```

## run the app

- click the triangle that is placed on the right top
- access to http://localhost:5222 (default)

## Model

## Controller

- IActionResult index() <!-- pointing to index page -->
- IActionResult Privacy() <!-- pointing to privacy page -->

## Tag Helper
enable server side code to create and render html element and allows us to interact with models
```
<input asp-for="" />

<span asp-validation-for="Name" type="text"></span>
```

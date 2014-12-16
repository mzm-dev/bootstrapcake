Cake Shell Template with Bootstrap Style
========================================

CakePHP’s Bake console is another effort to get you up and running in CakePHP – fast. The Bake console can create any of CakePHP’s basic ingredients: models, views and controllers. And we aren’t just talking skeleton classes: Bake can create a fully functional application in just a few minutes. In fact, Bake is a natural step to take once an application has been scaffolded.

Bootstrapcake is a shell template for rapidly developing beautiful Bootstrap themed CakePHP applications through the CakePHP console. The default template uses the ugly CakePHP styling but this template makes your app look beautiful by default.


Requirements
============

* CakePHP >= 2.3
* Bootstrap >= 3.0
 
Setup
=====


* Extract the files into the proper directory
    + /app/Console/Templates/bootstrap/
    + /app/View/Elements
    + /app/View/Layouts
* Update your App Controller (app/Controller/AppController.php) to use the Bootstrap layout

```php
class AppController extends Controller {
    public function beforeFilter(){
        $this->layout = 'bootstrapcake';
    }
}
```
* Start baking! ([Code Generation with Bake](http://book.cakephp.org/2.0/en/console-and-shells/code-generation-with-bake.html))
* Make sure you select the bootstrap template when prompted

# Cake PHP snippets
Visual Studio Code snippets code example for Cake PHP 2 & 3

![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/BubbleKID.cakephp-snippets.svg) ![License](https://img.shields.io/github/license/BubbleKID/vscode-cakephp-snippets.svg)

## Controller

| Snippet                  | Prefix     | Snippet                                    |
|--------------------------|------------|-------------------------------------------|
| `var_dump`               | vd         | var_dump();                            |
| `debug`                  | db         | debug();                               |
| `find`                   | find       | $this->Model->find('all');                |
| `data`                   | data       | $this->request->data                      |
| `save`                   | save       | $this->Model->save()                        |
| `pr`                     | pr         | pr();exit;                               |
| `set`                    | set        | $this->set();                            |
| `flash`                  | flash      | $this->Session->flash();              |
| `check`                  | check      | $this->Session->check();              |
| `delete`                  | delete      | $this->Session->delete();              |
| `destroy`                  | destroy      | $this->Session->destroy();              |
| `setFlash`                  | setFlash      | $this->Session->setFlash();              |
| `write`                  | write      | $this->Session->write();              |
| `read`                  | read      | $this->Session->read();              |
| `read`                  | read      | $this->Session->read();              |
| `conditions`             | conditions | 'conditions' => array('Model.id =>$id)    |
| `order`                  | order      | 'order' => array('Model.id' => 'ASC')     |
| `contain`                | conatain   | 'contain' => array('Model')               |
| `url-array`              | url        | array('controller' => '', 'action' => '') |
| `$this->request`         | request    | $this->request                            |
| `$this->redirect`        | redirect   | $this->redirect                           |
| `$this->request->params` | params     | $this->request->$params                   |
| `$this->request->query`  | query      | $this->request->query                     |

## View

| Snippet   | Prefix  | Snippet                                                                               |
|-----------|---------|---------------------------------------------------------------------------------------|
| `input`   | cinput  | $this->Form->input('field');                                                          |
| `create`  | create  | $this->Form->create('Model');                                                         |
| `submit`  | csubmit | $this->Form->submit(__(Save));                                                        |
| `element` | element | $this->element('file');                                                               |
| `link`    | clink   | $this->Html->link('title', array('controller' => 'controller', 'action => 'action')); |


## View(HTML)

| Snippet   | Prefix  | Snippet                                                                                                |
|-----------|---------|-------------------------------------------------------------------------------------------------------|
| `input`   | cinput  | \<\?php echo $this->Form->input('field'); ?>                                                          |
| `create`  | create  | \<\?php echo $this->Form->create('Model'); ?>                                                         |
| `submit`  | csubmit | \<\?php echo $this->Form->submit(__(Save));  ?>                                                       |
| `element` | element | \<\?php echo $this->element('file'); ?>                                                               |
| `link`    | clink   | \<\?php echo $this->Html->link('title', array('controller' => 'controller', 'action => 'action')); ?> |


## Model

| Snippet               | Prefix     | Snippet                                                                                                                                                                                                                                                        |
|-----------------------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `belongsTo`           | bt         | public $belongsTo = array( <br>   &nbsp;&nbsp;'classname' => array( <br>   &nbsp;&nbsp; 'foreignKey' => &nbsp;&nbsp;&nbsp;&nbsp;'foreign_key',   <br> &nbsp;&nbsp;&nbsp;&nbsp;'className' => &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'className'  <br>));         |
| `hasMany`             | hm         | public $hasMany = array(<br>  'className' => array(<br>    'className' => 'className',<br>    'dependent' => true<br>  ));                                                                                                                                    |
| `hasAndBelongsToMany` | habtm      | public $hasAndBelongsToMany = array(<br>  'className' => array(<br>    'className' => 'className', <br>    'joinTable' => 'join_table',<br>    'foreignKey' => <br>foreign_key', <br>    'associationForeignKey' => ,<br> association_foreign_key', <br>  )); |
| `validate`            | validate   | $this->element('file');                                                                                                                                                                                                                                       |
| `validation`          | validation | public validate = array( <br>  'field' => array( <br>    'rule' => 'ruleName', <br>    'message' => <br>message' <br>  ));                                                                                                                                    |
| `actsAs`              | act        | public $actsAs = array( );                                                                                                                                                                                                                                    |
| `App::uses`           | uses       | App::uses('AppModel', 'Model');                                                                                                                                                                                                                               |


Base on [vicocamacho/cakephp-snippets](https://github.com/vicocamacho/cakephp-snippets) and [openam/SublimeCakePHP](  https://github.com/openam/SublimeCakePHP)

## License

Please read [License](LICENSE.md) for more information
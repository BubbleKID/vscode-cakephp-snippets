
<h1 align="center">
  <br>
    <img src="https://github.com/BubbleKID/vscode-cakephp-snippets/blob/master/images/cakephp.png?raw=true" alt="logo" width="200">
  <br>
  Cake PHP snippets for VS Code
  <br>
  <br>
</h1>

<h4 align="center">Visual Studio Code snippets code example for Cake PHP 2 & 3
</h4> 
<p align="center">
  <img src="https://img.shields.io/visual-studio-marketplace/v/BubbleKID.cakephp-snippets.svg" alt="Visual Studio Marketplace Version"/>
  <img src="https://img.shields.io/github/license/BubbleKID/vscode-cakephp-snippets.svg" alt="License"/>
</p>


## Controller

| Snippet                  | Prefix       | Snippet                                   |
|--------------------------|--------------|-------------------------------------------|
| `var_dump`               | vd           | var_dump();                               |
| `debug`                  | db           | debug();                                  |
| `find`                   | find         | $this->Model->find('all');                |
| `data`                   | data         | $this->request->data                      |
| `save`                   | save         | $this->Model->save()                      |
| `pr`                     | pr           | pr();exit;                                |
| `set`                    | set          | $this->set();                             |
| `allow`                  | allow        | $this->->Auth->allow()                    |
| `authenticate`           | authenticate | $this->->Auth->authenticate()             |
| `deny`                   | deny         | $this->->Auth->deny()                     |
| `loggedIn`               | loggedIn     | $this->->Auth->loggedIn()                 |
| `login`                  | login        | $this->->Auth->login()                    |
| `logout`                 | logout       | $this->->Auth->logout()                   |
| `mapActions`             | mapActions   | $this->->Auth->mapActions()               |
| `redirectUrl`            | redirectUrl  | $this->->Auth->redirectUrl()              |
| `authenticate`           | authenticate | $this->->Auth->authenticate()             |
| `flash`                  | flash        | $this->Session->flash();                  |
| `check`                  | check        | $this->Session->check();                  |
| `delete`                 | delete       | $this->Session->delete();                 |
| `destroy`                | destroy      | $this->Session->destroy();                |
| `setFlash`               | setFlash     | $this->Session->setFlash();               |
| `write`                  | write        | $this->Session->write();                  |
| `read`                   | read         | $this->Session->read();                   |
| `read`                   | read         | $this->Session->read();                   |
| `conditions`             | conditions   | 'conditions' => array('Model.id =>$id)    |
| `order`                  | order        | 'order' => array('Model.id' => 'ASC')     |
| `contain`                | conatain     | 'contain' => array('Model')               |
| `url-array`              | url          | array('controller' => '', 'action' => '') |
| `$this->request`         | request      | $this->request                            |
| `$this->redirect`        | redirect     | $this->redirect                           |
| `$this->request->params` | params       | $this->request->$params                   |
| `$this->request->query`  | query        | $this->request->query                     |

## View

| Snippet   | Prefix  | Snippet                                                                               |
|-----------|---------|---------------------------------------------------------------------------------------|
| `input`   | cinput  | $this->Form->input('field');                                                          |
| `create`  | create  | $this->Form->create('Model');                                                         |
| `submit`  | csubmit | $this->Form->submit(__(Save));                                                        |
| `element` | element | $this->element('file');                                                               |
| `link`    | clink   | $this->Html->link('title', array('controller' => 'controller', 'action => 'action')); |


## View(HTML)

| Snippet   | Prefix  | Snippet                                                                                               |
|-----------|---------|-------------------------------------------------------------------------------------------------------|
| `input`   | cinput  | \<\?php echo $this->Form->input('field'); ?>                                                          |
| `create`  | create  | \<\?php echo $this->Form->create('Model'); ?>                                                         |
| `submit`  | csubmit | \<\?php echo $this->Form->submit(__(Save));  ?>                                                       |
| `element` | element | \<\?php echo $this->element('file'); ?>                                                               |
| `link`    | clink   | \<\?php echo $this->Html->link('title', array('controller' => 'controller', 'action => 'action')); ?> |


## Model

| Snippet               | Prefix     | Snippet                                                                                                                                                                                                                                                       |
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
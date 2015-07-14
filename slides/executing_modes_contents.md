## Modo interactivo

```python
>>>> print "hola mundo"
hola mundo
>>> 37*42
1554
>>> for i in range(5):
...
    print i
...
0
1
2
3
4
>>>
```

<ul>
<li class="fragment fade-in">
El intérprete está continuamente listo para ejecutar
</li>
<li class="fragment fade-in">
Ejecuta lo que se escriba
</li>
</ul>



## Modo interactivo (II)

Algunas consideraciones sobre el modo interactivo

<a class="showTip @largeTip" href="#"></a>
<div style="display: none;" class="statusExpandedTip hideDialog">
<p>
Large tip for element
</p>
</div>

```python
>>> print "hello world"
hello world
>>> 37*42
1554
>>> for i in range(5):
...     print i
...
0
1
2
3
4
>>>
```

<div id="tooltip_1" class="my_tooltip" style="position:relative;top:-330px; width:32px;height:32px;  z-index:100000 "></div>
<div id="tooltip_2" class="my_tooltip" style="position:relative;top:-250px; width:32px;height:32px;  z-index:100001 "></div>
<div id="tooltip_3" class="my_tooltip" style="position:relative;top:-250px; left: 200px; width:32px;height:32px;  z-index:100002 "></div>

<div style="display: none;">
    <div id="data_tooltip_1">
        <strong> >>> </strong> es el prompt del intérprete e indica el comienzo de una nueva instrucción
    </div>
    <div id="data_tooltip_2">
        <bold>...</bold>  es el prompt del intérprete para continuar una instrucción  (puede ser negro en algunas herramientas)
    </div>
    <div id="data_tooltip_3">
        Introduce una linea en blanco para acabar de teclear y ejecutar
    </div>
</div>
                 
note:
    Put your speaker notes here.
    You can see them pressing 's'.



## Como programa

```python 
> vi hola.py
#!/usr/bin/python
# My first python program
print "Hello, World!\n"
> python hola.py
Hello, World!\n
```																

<ul>
<li class="fragment fade-in">
Los ficheros tienen extensión `.py`
</li>
<li class="fragment fade-in">
Se pueden crear con cualquier editor de texto (e.g., `vi` o `emacs`)
</li>
<li class="fragment fade-in">
Ejecutamos invocando `python nombre_fichero.py`
</li>
<li class="fragment fade-in">
También podemos usar otros editores...
</li>
</ul>



## Como programa

[Usando Idle](http://www.python.org/idle/)

<a class="fancybox" href="img/idle2.png" data-fancybox-group="gallery" title="SPE">
<img height="400px" src="img/idle2.png" alt="SPE">
</a>



## Como programa

[SPE IDE - Stani's Python Editor](http://sourceforge.net/projects/spe/)

<a class="fancybox" href="img/spe.png" data-fancybox-group="gallery" title="SPE">
<img height="300px" src="img/spe.redimensionado.png" alt="SPE">
</a>

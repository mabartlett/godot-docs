:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the PlaneMesh.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_PlaneMesh:

PlaneMesh
=========

**Inherits:** :ref:`PrimitiveMesh<class_PrimitiveMesh>` **<** :ref:`Mesh<class_Mesh>` **<** :ref:`Resource<class_Resource>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

Class representing a planar :ref:`PrimitiveMesh<class_PrimitiveMesh>`.

Description
-----------

Class representing a planar :ref:`PrimitiveMesh<class_PrimitiveMesh>`. This flat mesh does not have a thickness. By default, this mesh is aligned on the X and Z axes; this default rotation isn't suited for use with billboarded materials. For billboarded materials, use :ref:`QuadMesh<class_QuadMesh>` instead.

Properties
----------

+-------------------------------+------------------------------------------------------------------+---------------------+
| :ref:`Vector2<class_Vector2>` | :ref:`size<class_PlaneMesh_property_size>`                       | ``Vector2( 2, 2 )`` |
+-------------------------------+------------------------------------------------------------------+---------------------+
| :ref:`int<class_int>`         | :ref:`subdivide_depth<class_PlaneMesh_property_subdivide_depth>` | ``0``               |
+-------------------------------+------------------------------------------------------------------+---------------------+
| :ref:`int<class_int>`         | :ref:`subdivide_width<class_PlaneMesh_property_subdivide_width>` | ``0``               |
+-------------------------------+------------------------------------------------------------------+---------------------+

Property Descriptions
---------------------

.. _class_PlaneMesh_property_size:

- :ref:`Vector2<class_Vector2>` **size**

+-----------+---------------------+
| *Default* | ``Vector2( 2, 2 )`` |
+-----------+---------------------+
| *Setter*  | set_size(value)     |
+-----------+---------------------+
| *Getter*  | get_size()          |
+-----------+---------------------+

Size of the generated plane.

----

.. _class_PlaneMesh_property_subdivide_depth:

- :ref:`int<class_int>` **subdivide_depth**

+-----------+----------------------------+
| *Default* | ``0``                      |
+-----------+----------------------------+
| *Setter*  | set_subdivide_depth(value) |
+-----------+----------------------------+
| *Getter*  | get_subdivide_depth()      |
+-----------+----------------------------+

Number of subdivision along the Z axis.

----

.. _class_PlaneMesh_property_subdivide_width:

- :ref:`int<class_int>` **subdivide_width**

+-----------+----------------------------+
| *Default* | ``0``                      |
+-----------+----------------------------+
| *Setter*  | set_subdivide_width(value) |
+-----------+----------------------------+
| *Getter*  | get_subdivide_width()      |
+-----------+----------------------------+

Number of subdivision along the X axis.


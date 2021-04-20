Dexterous Hand meshes
======================

.. table::
   :class: tight-table
   
   +--------------------------------------------------+--------------------------------------------------+--------------------------------------------------+
   | Icon picture                                     | Icon text                                        |  Icon explanation                                | 
   +==================================================+==================================================+==================================================+
   | .. image:: ../img/log-icon.png                   | Shadow ROS Logs Saver and Uploader               | Saves ROS logs from server and NUC, uploads them |
   |    :width: 100                                   |                                                  | to Shadow servers and emails them to Shadow      |
   +--------------------------------------------------+--------------------------------------------------+--------------------------------------------------+
   | .. image:: ../img/hand-e.png                     | Launch Shadow Right Hand                         | Launches the right hand (container, ROS core,    |
   |    :width: 100                                   |                                                  | NUC hardware control loop, server GUI)           |
   +--------------------------------------------------+--------------------------------------------------+--------------------------------------------------+
   | .. image:: ../img/hand-e-left.png                | Launch Shadow Left Hand                          | Launches the left hand (container, ROS core,     |
   |    :width: 100                                   |                                                  | NUC hardware control loop, server GUI)           |
   +--------------------------------------------------+--------------------------------------------------+--------------------------------------------------+
   | .. image:: ../img/hand-e-bimanual.png            | Launch Shadow Bimanual Hands                     | Launches the both hands (container, ROS core,    |
   |    :width: 100                                   |                                                  | NUC hardware control loop, server GUI)           |
   +--------------------------------------------------+--------------------------------------------------+--------------------------------------------------+
   | .. image:: ../img/ROS_logo.png                   | Shadow NUC RQT                                   | Once the hand has been launched, this icon       |
   |    :width: 100                                   |                                                  | starts ROS RQT inside the NUC's docker container |
   +--------------------------------------------------+--------------------------------------------------+--------------------------------------------------+
   | .. image:: ../img/documentation_icon.png         | Dexterous Hand Documentation                     | Opens online documentation if internet connected |
   |    :width: 100                                   |                                                  | or offline documentation if no internet          |
   +--------------------------------------------------+--------------------------------------------------+--------------------------------------------------+
   | .. image:: ../img/close_icon.png                 | Shadow Close Everything                          | Cleanly stops ROS processes, closes containers,  |
   |    :width: 100                                   |                                                  | and closes all Shadow related terminals          |
   +--------------------------------------------------+--------------------------------------------------+--------------------------------------------------+


Fingers
===========  =========================================================  =========================================================
             Visual Mesh                                                Collision Mesh
-----------  ---------------------------------------------------------  ---------------------------------------------------------
  A    
===========  =========================================================  =========================================================
Distal       `cable_collision_mesh <hand/cable_collision_mesh.stl>`_    `cable_collision_mesh <hand/cable_collision_mesh.stl>`_
Middle   
Proximal      
===========  =========================================================  =========================================================



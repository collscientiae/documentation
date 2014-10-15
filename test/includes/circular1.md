title: Circular Includes 1

# This is level 1

include[includes.circular2]

Tail of includes, checking that the same can be included several times as siblings:

* include[includes.includeme]
    * include[includes.includeme]
    * include[includes.includeme]
    * include[includes.includeme]
* include[includes.includeme]
    * include[includes.includeme]
    * include[includes.includeme]
    * include[includes.includeme]


EOF Level 1
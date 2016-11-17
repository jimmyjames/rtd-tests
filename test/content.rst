============
Some Content
============

blah blah blah

.. code-block:: groovy

    def addThem(str1, str2) {
    // strings and numbers support the + operator
    return str1 + str2
    }

    def added = addThem("Smart", "Things")
    assert added == "SmartThings"

    def added2 = addThem(4, 2)
    assert added2 == 6

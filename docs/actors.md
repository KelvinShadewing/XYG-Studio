# <center>**Brux Scripting Reference Manual**</center>
## <center>Actors</center>



&nbsp;

* <a name="newActor"></a>**`newActor( type, x, y )`**

  Creates a new instance of an actor class. `type` should be the name of a class that extends `Actor`. Returns the ID number of the new instance to use with `actor[id]` to address an instance.

* <a name="deleteActor"></a>**`deleteActor( id )`**

  Deletes an actor instance with the ID number `id`.

* <a name="runActors"></a>**`runActors()`**

  Goes through every existing actor instance and executes their respective `run()` function.

* <a name="countActors"></a>**`countActors()`**

  Counts the number of active actor instances and returns the result.

* <a name="checkActor"></a>**`checkActor( id )`**

  Checks if an actor with the given `id` exists. Returns true if it does, false if no actor with that ID was found.

### Actor Members

**NOTE** These functions are predefined within `Actor`, and are called by `Actor` instances or within derived `Actor` class methods.
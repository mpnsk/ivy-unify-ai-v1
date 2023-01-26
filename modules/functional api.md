in the "functional" module ivy stores documentation and types of other framework functions.
These functions are not used explicitly, ivy uses a "[[backend handler]]" do address different namespaces with the same variable.
you just set the variable like
`ivy.set_backend("jax")` and it changes which framework is called

//TODO check whether it changes docs right in the IDE
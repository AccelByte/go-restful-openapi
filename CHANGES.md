# changes to the go-restful-openapi package

## v0.12.0

    - add support for time.Duration
    - Populate the swagger definition with the parameter's 'AllowableValues' as an enum (#53)
    - Fix for #19 MapModelTypeNameFunc has incomplete behavior
    - Merge paths with existing paths from other webServices (#48)
    - prevent array param.Type be overwritten in the else case below (#47)

## v0.11.0

    - Register pointer to array/slice of primitives as such rather than as reference to the primitive type definition. (#46)
    - Add support for map types using "additional properties" (#44) 

## <= v0.10.0

See `git log`.
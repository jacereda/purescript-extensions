## Module Extensions

#### `fail`

``` purescript
fail :: forall a. String -> a
```

#### `undef`

``` purescript
undef :: forall a. a
```

#### `unsafeTrace`

``` purescript
unsafeTrace :: forall a. String -> a -> a
```

#### `unsafeCoerce`

``` purescript
unsafeCoerce :: forall a b. a -> b
```

#### `mapM`

``` purescript
mapM :: forall a b m. (Monad m) => (a -> m b) -> Array a -> m (Array b)
```

#### `mapE`

``` purescript
mapE :: forall a b e. (a -> Eff e b) -> Array a -> Eff e (Array b)
```

Map with effects over an array of values.


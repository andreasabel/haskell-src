## 1.0.3.2

  - Support happy-1.20.

## 1.0.3.1

  - Support GHC 8.10 and base-4.14.

## 1.0.3.0

 - Add support for `MonadFail` & `Semigroup` proposals by
   adding respective instances for `P` and `Lex`.

 - Drop support for GHC versions prior to GHC 7.0.

 - Remove `-O2` from `ghc-options`.

## 1.0.2.0

 - Add support for GHC 7.10 & base-4.8

 - Add missing `Functor` & `Applicative` instances for `P` and `Lex`
   monads needed for AMP compatibility.

*****************
DRYlib for Kotlin
*****************

.. image:: https://img.shields.io/badge/license-Public%20Domain-blue.svg
   :alt: Project license
   :target: https://unlicense.org/

.. image:: https://img.shields.io/travis/dryproject/drylib.kt/master.svg
   :alt: Travis CI build status
   :target: https://travis-ci.org/dryproject/drylib.kt

|

http://drylib.org

Prerequisites
=============

* `Kotlin <https://en.wikipedia.org/wiki/Kotlin_(programming_language)>`__
  1.1+

Features
========

Caveats
=======

Installation
============

Usage
=====

::

   import dry.*

Reference
=========

``core``
--------

=============== ================================================================
DRY Symbol      Kotlin Symbol
=============== ================================================================
``bool``        ``dry.Bool`` (type alias for ``kotlin.Boolean``)
``char``        ``dry.Char`` (type alias for ``kotlin.Char``) (FIXME)
``complex``     ``dry.Complex`` (data class)
``float``       ``dry.Float`` (type alias for ``kotlin.Double``)
``float32``     ``dry.Float32`` (type alias for ``kotlin.Float``)
``float64``     ``dry.Float64`` (type alias for ``kotlin.Double``)
``int``         ``dry.Int`` (type alias for ``kotlin.Int``)
``int8``        ``dry.Int8`` (type alias for ``kotlin.Int``)
``int16``       ``dry.Int16`` (type alias for ``kotlin.Int``)
``int32``       ``dry.Int32`` (type alias for ``kotlin.Int``)
``int64``       ``dry.Int64`` (type alias for ``kotlin.Long``)
``int128``      ``dry.Int128`` (type alias for ``kotlin.Long``) (FIXME)
``integer``     ``dry.Integer`` (type alias for ``java.math.BigInteger``)
``natural``     ``dry.Natural`` (type alias for ``dry.Integer``)
``rational``    ``dry.Rational`` (data class)
``real``        ``dry.Real`` (type alias for ``java.math.BigDecimal``)
``word``        ``dry.Word`` (type alias for ``kotlin.Long``)
``word8``       ``dry.Word8`` (type alias for ``kotlin.Long``)
``word16``      ``dry.Word16`` (type alias for ``kotlin.Long``)
``word32``      ``dry.Word32`` (type alias for ``kotlin.Long``)
``word64``      ``dry.Word64`` (type alias for ``kotlin.Long``)
=============== ================================================================

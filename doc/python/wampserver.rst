Server
======

The classes :class:`autobahn.wamp.WampServerProtocol` and
:class:`autobahn.wamp.WampServerFactory` are the base classes
you derive from to implement WAMP servers.



Factory
-------

.. autoclass:: autobahn.wamp.WampServerFactory
   :members: dispatch,
             sessionIdsToProtos,
             protosToSessionIds,
             startFactory,
             stopFactory


Protocol
--------

.. autoclass:: autobahn.wamp.WampServerProtocol
   :members: onSessionOpen,
             dispatch,
             registerForRpc,
             registerMethodForRpc,
             registerProcedureForRpc,
             registerForPubSub,
             registerHandlerForPubSub,
             registerHandlerForSub,
             registerHandlerForPub

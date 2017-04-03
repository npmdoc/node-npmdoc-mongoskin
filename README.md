# api documentation for  [mongoskin (v2.1.0)](https://github.com/kissjs/node-mongoskin)  [![npm package](https://img.shields.io/npm/v/npmdoc-mongoskin.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mongoskin) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mongoskin.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mongoskin)
#### The future layer above node-mongodb-native

[![NPM](https://nodei.co/npm/mongoskin.png?downloads=true)](https://www.npmjs.com/package/mongoskin)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongoskin/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-mongoskin_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongoskin/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mongoskin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mongoskin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gui Lin",
        "email": "guileen@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/kissjs/node-mongoskin/issues"
    },
    "contributors": [
        {
            "name": "Gui Lin",
            "email": "guileen@gmail.com",
            "url": "https://github.com/guileen"
        },
        {
            "name": "François de Metz",
            "email": "francois@2metz.fr",
            "url": "https://github.com/francois2metz"
        },
        {
            "name": "fengmk2",
            "email": "fengmk2@gmail.com",
            "url": "http://fengmk2.github.com"
        },
        {
            "name": "Quang Van",
            "email": "quangvvv@gmail.com",
            "url": "https://github.com/quangv"
        },
        {
            "name": "Matt Perpick",
            "email": "clutchski@gmail.com",
            "url": "https://github.com/clutchski"
        },
        {
            "name": "humanchimp",
            "email": "morphcham@gmail.com",
            "url": "https://github.com/humanchimp"
        },
        {
            "name": "Joe Faber",
            "email": "joe.faber@mandiant.com",
            "url": "https://github.com/jlfaber"
        },
        {
            "name": "Harvey McQueen",
            "email": "hmcqueen@gmail.com",
            "url": "https://github.com/hmcqueen"
        },
        {
            "name": "Paul Gebheim",
            "email": "pgebheim@monkeyinferno.com",
            "url": "https://github.com/paulirish"
        },
        {
            "name": "Aneil Mallavarapu",
            "email": "aneil@blipboard.com",
            "url": "https://github.com/amallavarapu"
        },
        {
            "name": "wmertens",
            "email": "Wout.Mertens@gmail.com",
            "url": "https://github.com/wmertens"
        },
        {
            "name": "Rakshit Menpara",
            "email": "deltasquare4@gmail.com",
            "url": "https://github.com/deltasquare4"
        }
    ],
    "dependencies": {},
    "description": "The future layer above node-mongodb-native",
    "devDependencies": {
        "coveralls": "~2.10.0",
        "istanbul": "0.3.17",
        "mocha": "~1.17.1",
        "mocha-lcov-reporter": "0.0.1",
        "mongodb": "^2.0",
        "should": "~3.1.2",
        "travis-cov": "~0.2.5"
    },
    "directories": {
        "example": "./examples",
        "lib": "./lib/mongoskin"
    },
    "dist": {
        "shasum": "1fda6814b21de53e36b4396f6126c979c5e9ee60",
        "tarball": "https://registry.npmjs.org/mongoskin/-/mongoskin-2.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "gitHead": "60d677e287c8841fd5aa028b4a5ed6e4a6108467",
    "homepage": "https://github.com/kissjs/node-mongoskin",
    "keywords": [
        "mongodb",
        "database",
        "nosql"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "guileen",
            "email": "guileen@gmail.com"
        },
        {
            "name": "fengmk2",
            "email": "fengmk2@gmail.com"
        },
        {
            "name": "vkarpov15",
            "email": "val@karpov.io"
        }
    ],
    "name": "mongoskin",
    "optionalDependencies": {},
    "peerDependencies": {
        "mongodb": "^2.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/kissjs/node-mongoskin.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha",
        "test": "mocha"
    },
    "version": "2.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module mongoskin](#apidoc.module.mongoskin)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Admin ()](#apidoc.element.mongoskin.Admin)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>BSONRegExp (pattern, options)](#apidoc.element.mongoskin.BSONRegExp)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Binary (buffer, subType)](#apidoc.element.mongoskin.Binary)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Chunk (file, mongoObject, writeConcern)](#apidoc.element.mongoskin.Chunk)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Code (code, scope)](#apidoc.element.mongoskin.Code)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Collection ()](#apidoc.element.mongoskin.Collection)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>CoreConnection (messageHandler, options)](#apidoc.element.mongoskin.CoreConnection)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>CoreServer (options)](#apidoc.element.mongoskin.CoreServer)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Cursor ()](#apidoc.element.mongoskin.Cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>DBRef (namespace, oid, db)](#apidoc.element.mongoskin.DBRef)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Db ()](#apidoc.element.mongoskin.Db)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Decimal128 (bytes)](#apidoc.element.mongoskin.Decimal128)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Double (value)](#apidoc.element.mongoskin.Double)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>GridFSBucket (db, options)](#apidoc.element.mongoskin.GridFSBucket)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>GridStore ()](#apidoc.element.mongoskin.GridStore)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Int32 (value)](#apidoc.element.mongoskin.Int32)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Logger (className, options)](#apidoc.element.mongoskin.Logger)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Long (low, high)](#apidoc.element.mongoskin.Long)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Map ()](#apidoc.element.mongoskin.Map)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>MaxKey ()](#apidoc.element.mongoskin.MaxKey)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>MinKey ()](#apidoc.element.mongoskin.MinKey)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>MongoClient ()](#apidoc.element.mongoskin.MongoClient)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>MongoError (message)](#apidoc.element.mongoskin.MongoError)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Mongos (servers, options)](#apidoc.element.mongoskin.Mongos)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>ObjectID (id)](#apidoc.element.mongoskin.ObjectID)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>ObjectId (id)](#apidoc.element.mongoskin.ObjectId)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>ReadPreference (mode, tags, options)](#apidoc.element.mongoskin.ReadPreference)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>ReplSet (servers, options)](#apidoc.element.mongoskin.ReplSet)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Server (host, port, options)](#apidoc.element.mongoskin.Server)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Symbol (value)](#apidoc.element.mongoskin.Symbol)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Timestamp (low, high)](#apidoc.element.mongoskin.Timestamp)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>connect (url, options, callback)](#apidoc.element.mongoskin.connect)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>connect.Admin (db, topology, promiseLibrary)](#apidoc.element.mongoskin.connect.Admin)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>connect.Collection (db, topology, dbName, name, pkFactory, options)](#apidoc.element.mongoskin.connect.Collection)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>connect.Cursor (bson, ns, cmd, options, topology, topologyOptions)](#apidoc.element.mongoskin.connect.Cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>connect.Db (databaseName, topology, options)](#apidoc.element.mongoskin.connect.Db)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>connect.GridStore (db, id, filename, mode, options)](#apidoc.element.mongoskin.connect.GridStore)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>connect.MongoClient ()](#apidoc.element.mongoskin.connect.MongoClient)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>db ()](#apidoc.element.mongoskin.db)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>instrument (options, callback)](#apidoc.element.mongoskin.instrument)
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Admin.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Binary.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Chunk.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Code.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Collection.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>CoreConnection.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>CoreServer.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Cursor.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>DBRef.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Db.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Decimal128.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Double.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>GridFSBucket.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>GridStore.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Int32.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Logger.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Long.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>MongoClient.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Mongos.define
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Mongos.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>ObjectID.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>ReadPreference.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>ReplSet.define
1.  object <span class="apidocSignatureSpan">mongoskin.</span>ReplSet.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Server.define
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Server.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Symbol.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>Timestamp.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>admin
1.  object <span class="apidocSignatureSpan">mongoskin.</span>collection
1.  object <span class="apidocSignatureSpan">mongoskin.</span>connect.Admin.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>connect.Collection.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>connect.Cursor.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>connect.Db.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>connect.GridStore.prototype
1.  object <span class="apidocSignatureSpan">mongoskin.</span>cursor
1.  object <span class="apidocSignatureSpan">mongoskin.</span>grid_store
1.  object <span class="apidocSignatureSpan">mongoskin.</span>helper
1.  object <span class="apidocSignatureSpan">mongoskin.</span>mongo_client
1.  object <span class="apidocSignatureSpan">mongoskin.</span>utils

#### [module mongoskin.Admin](#apidoc.module.mongoskin.Admin)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Admin ()](#apidoc.element.mongoskin.Admin.Admin)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.</span>_bindGetter (propName)](#apidoc.element.mongoskin.Admin._bindGetter)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.</span>_bindMethod (propName)](#apidoc.element.mongoskin.Admin._bindMethod)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.</span>_bindSetter (propName)](#apidoc.element.mongoskin.Admin._bindSetter)
1.  string <span class="apidocSignatureSpan">mongoskin.Admin.</span>_class_name

#### [module mongoskin.Admin.prototype](#apidoc.module.mongoskin.Admin.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>_close (callback)](#apidoc.element.mongoskin.Admin.prototype._close)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>_open (callback)](#apidoc.element.mongoskin.Admin.prototype._open)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>addUser ()](#apidoc.element.mongoskin.Admin.prototype.addUser)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>authenticate ()](#apidoc.element.mongoskin.Admin.prototype.authenticate)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>buildInfo ()](#apidoc.element.mongoskin.Admin.prototype.buildInfo)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>close (callback)](#apidoc.element.mongoskin.Admin.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>command ()](#apidoc.element.mongoskin.Admin.prototype.command)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>isOpen ()](#apidoc.element.mongoskin.Admin.prototype.isOpen)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>listDatabases ()](#apidoc.element.mongoskin.Admin.prototype.listDatabases)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>logout ()](#apidoc.element.mongoskin.Admin.prototype.logout)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>open (callback)](#apidoc.element.mongoskin.Admin.prototype.open)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>ping ()](#apidoc.element.mongoskin.Admin.prototype.ping)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>profilingInfo ()](#apidoc.element.mongoskin.Admin.prototype.profilingInfo)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>profilingLevel ()](#apidoc.element.mongoskin.Admin.prototype.profilingLevel)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>removeUser ()](#apidoc.element.mongoskin.Admin.prototype.removeUser)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>replSetGetStatus ()](#apidoc.element.mongoskin.Admin.prototype.replSetGetStatus)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>serverInfo ()](#apidoc.element.mongoskin.Admin.prototype.serverInfo)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>serverStatus ()](#apidoc.element.mongoskin.Admin.prototype.serverStatus)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>setProfilingLevel ()](#apidoc.element.mongoskin.Admin.prototype.setProfilingLevel)
1.  [function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>validateCollection ()](#apidoc.element.mongoskin.Admin.prototype.validateCollection)

#### [module mongoskin.BSONRegExp](#apidoc.module.mongoskin.BSONRegExp)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>BSONRegExp (pattern, options)](#apidoc.element.mongoskin.BSONRegExp.BSONRegExp)

#### [module mongoskin.Binary](#apidoc.module.mongoskin.Binary)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Binary (buffer, subType)](#apidoc.element.mongoskin.Binary.Binary)
1.  number <span class="apidocSignatureSpan">mongoskin.Binary.</span>BUFFER_SIZE
1.  number <span class="apidocSignatureSpan">mongoskin.Binary.</span>SUBTYPE_BYTE_ARRAY
1.  number <span class="apidocSignatureSpan">mongoskin.Binary.</span>SUBTYPE_DEFAULT
1.  number <span class="apidocSignatureSpan">mongoskin.Binary.</span>SUBTYPE_FUNCTION
1.  number <span class="apidocSignatureSpan">mongoskin.Binary.</span>SUBTYPE_MD5
1.  number <span class="apidocSignatureSpan">mongoskin.Binary.</span>SUBTYPE_USER_DEFINED
1.  number <span class="apidocSignatureSpan">mongoskin.Binary.</span>SUBTYPE_UUID
1.  number <span class="apidocSignatureSpan">mongoskin.Binary.</span>SUBTYPE_UUID_OLD

#### [module mongoskin.Binary.prototype](#apidoc.module.mongoskin.Binary.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>length ()](#apidoc.element.mongoskin.Binary.prototype.length)
1.  [function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>put (byte_value)](#apidoc.element.mongoskin.Binary.prototype.put)
1.  [function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>read (position, length)](#apidoc.element.mongoskin.Binary.prototype.read)
1.  [function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Binary.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>toString (format)](#apidoc.element.mongoskin.Binary.prototype.toString)
1.  [function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>value (asRaw)](#apidoc.element.mongoskin.Binary.prototype.value)
1.  [function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>write (string, offset)](#apidoc.element.mongoskin.Binary.prototype.write)

#### [module mongoskin.Chunk](#apidoc.module.mongoskin.Chunk)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Chunk (file, mongoObject, writeConcern)](#apidoc.element.mongoskin.Chunk.Chunk)
1.  number <span class="apidocSignatureSpan">mongoskin.Chunk.</span>DEFAULT_CHUNK_SIZE

#### [module mongoskin.Chunk.prototype](#apidoc.module.mongoskin.Chunk.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>buildMongoObject (callback)](#apidoc.element.mongoskin.Chunk.prototype.buildMongoObject)
1.  [function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>eof ()](#apidoc.element.mongoskin.Chunk.prototype.eof)
1.  [function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>getc ()](#apidoc.element.mongoskin.Chunk.prototype.getc)
1.  [function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>length ()](#apidoc.element.mongoskin.Chunk.prototype.length)
1.  [function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>read (length)](#apidoc.element.mongoskin.Chunk.prototype.read)
1.  [function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>readSlice (length)](#apidoc.element.mongoskin.Chunk.prototype.readSlice)
1.  [function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>rewind ()](#apidoc.element.mongoskin.Chunk.prototype.rewind)
1.  [function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>save (options, callback)](#apidoc.element.mongoskin.Chunk.prototype.save)
1.  [function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>write (data, callback)](#apidoc.element.mongoskin.Chunk.prototype.write)

#### [module mongoskin.Code](#apidoc.module.mongoskin.Code)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Code (code, scope)](#apidoc.element.mongoskin.Code.Code)

#### [module mongoskin.Code.prototype](#apidoc.module.mongoskin.Code.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Code.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Code.prototype.toJSON)

#### [module mongoskin.Collection](#apidoc.module.mongoskin.Collection)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Collection ()](#apidoc.element.mongoskin.Collection.Collection)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.</span>_bindGetter (propName)](#apidoc.element.mongoskin.Collection._bindGetter)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.</span>_bindMethod (propName)](#apidoc.element.mongoskin.Collection._bindMethod)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.</span>_bindSetter (propName)](#apidoc.element.mongoskin.Collection._bindSetter)
1.  string <span class="apidocSignatureSpan">mongoskin.Collection.</span>_class_name

#### [module mongoskin.Collection.prototype](#apidoc.module.mongoskin.Collection.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>_close (callback)](#apidoc.element.mongoskin.Collection.prototype._close)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>_find ()](#apidoc.element.mongoskin.Collection.prototype._find)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>_open (callback)](#apidoc.element.mongoskin.Collection.prototype._open)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>_operateById (methodName, id, args)](#apidoc.element.mongoskin.Collection.prototype._operateById)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>aggregate ()](#apidoc.element.mongoskin.Collection.prototype.aggregate)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>bind (extendObject)](#apidoc.element.mongoskin.Collection.prototype.bind)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>bulkWrite ()](#apidoc.element.mongoskin.Collection.prototype.bulkWrite)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>close (callback)](#apidoc.element.mongoskin.Collection.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>count ()](#apidoc.element.mongoskin.Collection.prototype.count)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>createIndex ()](#apidoc.element.mongoskin.Collection.prototype.createIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>createIndexes ()](#apidoc.element.mongoskin.Collection.prototype.createIndexes)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>deleteMany ()](#apidoc.element.mongoskin.Collection.prototype.deleteMany)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>deleteOne ()](#apidoc.element.mongoskin.Collection.prototype.deleteOne)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>distinct ()](#apidoc.element.mongoskin.Collection.prototype.distinct)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>drop ()](#apidoc.element.mongoskin.Collection.prototype.drop)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>dropAllIndexes ()](#apidoc.element.mongoskin.Collection.prototype.dropAllIndexes)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>dropIndex ()](#apidoc.element.mongoskin.Collection.prototype.dropIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>dropIndexes ()](#apidoc.element.mongoskin.Collection.prototype.dropIndexes)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>ensureIndex ()](#apidoc.element.mongoskin.Collection.prototype.ensureIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>find (query, options, callback)](#apidoc.element.mongoskin.Collection.prototype.find)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findAndModify ()](#apidoc.element.mongoskin.Collection.prototype.findAndModify)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findAndRemove ()](#apidoc.element.mongoskin.Collection.prototype.findAndRemove)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findById (id, callback)](#apidoc.element.mongoskin.Collection.prototype.findById)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findEach (query, options, eachCallback)](#apidoc.element.mongoskin.Collection.prototype.findEach)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findItems (query, options, callback)](#apidoc.element.mongoskin.Collection.prototype.findItems)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findOne ()](#apidoc.element.mongoskin.Collection.prototype.findOne)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findOneAndDelete ()](#apidoc.element.mongoskin.Collection.prototype.findOneAndDelete)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findOneAndReplace ()](#apidoc.element.mongoskin.Collection.prototype.findOneAndReplace)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findOneAndUpdate ()](#apidoc.element.mongoskin.Collection.prototype.findOneAndUpdate)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>geoHaystackSearch ()](#apidoc.element.mongoskin.Collection.prototype.geoHaystackSearch)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>geoNear ()](#apidoc.element.mongoskin.Collection.prototype.geoNear)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>group ()](#apidoc.element.mongoskin.Collection.prototype.group)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>indexExists ()](#apidoc.element.mongoskin.Collection.prototype.indexExists)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>indexInformation ()](#apidoc.element.mongoskin.Collection.prototype.indexInformation)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>indexes ()](#apidoc.element.mongoskin.Collection.prototype.indexes)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>initializeOrderedBulkOp ()](#apidoc.element.mongoskin.Collection.prototype.initializeOrderedBulkOp)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>initializeUnorderedBulkOp ()](#apidoc.element.mongoskin.Collection.prototype.initializeUnorderedBulkOp)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>insert ()](#apidoc.element.mongoskin.Collection.prototype.insert)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>insertMany ()](#apidoc.element.mongoskin.Collection.prototype.insertMany)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>insertOne ()](#apidoc.element.mongoskin.Collection.prototype.insertOne)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>isCapped ()](#apidoc.element.mongoskin.Collection.prototype.isCapped)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>isOpen ()](#apidoc.element.mongoskin.Collection.prototype.isOpen)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>listIndexes ()](#apidoc.element.mongoskin.Collection.prototype.listIndexes)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>mapReduce ()](#apidoc.element.mongoskin.Collection.prototype.mapReduce)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>open (callback)](#apidoc.element.mongoskin.Collection.prototype.open)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>options ()](#apidoc.element.mongoskin.Collection.prototype.options)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>parallelCollectionScan ()](#apidoc.element.mongoskin.Collection.prototype.parallelCollectionScan)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>reIndex ()](#apidoc.element.mongoskin.Collection.prototype.reIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>remove ()](#apidoc.element.mongoskin.Collection.prototype.remove)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>removeById (id, callback)](#apidoc.element.mongoskin.Collection.prototype.removeById)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>removeMany ()](#apidoc.element.mongoskin.Collection.prototype.removeMany)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>removeOne ()](#apidoc.element.mongoskin.Collection.prototype.removeOne)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>rename ()](#apidoc.element.mongoskin.Collection.prototype.rename)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>replaceOne ()](#apidoc.element.mongoskin.Collection.prototype.replaceOne)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>save ()](#apidoc.element.mongoskin.Collection.prototype.save)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>stats ()](#apidoc.element.mongoskin.Collection.prototype.stats)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>update ()](#apidoc.element.mongoskin.Collection.prototype.update)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>updateById (id, doc, callback)](#apidoc.element.mongoskin.Collection.prototype.updateById)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>updateMany ()](#apidoc.element.mongoskin.Collection.prototype.updateMany)
1.  [function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>updateOne ()](#apidoc.element.mongoskin.Collection.prototype.updateOne)

#### [module mongoskin.CoreConnection](#apidoc.module.mongoskin.CoreConnection)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>CoreConnection (messageHandler, options)](#apidoc.element.mongoskin.CoreConnection.CoreConnection)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.</span>connections ()](#apidoc.element.mongoskin.CoreConnection.connections)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.</span>disableConnectionAccounting ()](#apidoc.element.mongoskin.CoreConnection.disableConnectionAccounting)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.</span>enableConnectionAccounting ()](#apidoc.element.mongoskin.CoreConnection.enableConnectionAccounting)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.</span>super_ ()](#apidoc.element.mongoskin.CoreConnection.super_)

#### [module mongoskin.CoreConnection.prototype](#apidoc.module.mongoskin.CoreConnection.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>connect (_options)](#apidoc.element.mongoskin.CoreConnection.prototype.connect)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>destroy ()](#apidoc.element.mongoskin.CoreConnection.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>isConnected ()](#apidoc.element.mongoskin.CoreConnection.prototype.isConnected)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>resetSocketTimeout ()](#apidoc.element.mongoskin.CoreConnection.prototype.resetSocketTimeout)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>setSocketTimeout (value)](#apidoc.element.mongoskin.CoreConnection.prototype.setSocketTimeout)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>toJSON ()](#apidoc.element.mongoskin.CoreConnection.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>toString ()](#apidoc.element.mongoskin.CoreConnection.prototype.toString)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>unref ()](#apidoc.element.mongoskin.CoreConnection.prototype.unref)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>write (buffer)](#apidoc.element.mongoskin.CoreConnection.prototype.write)

#### [module mongoskin.CoreServer](#apidoc.module.mongoskin.CoreServer)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>CoreServer (options)](#apidoc.element.mongoskin.CoreServer.CoreServer)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.</span>disableServerAccounting ()](#apidoc.element.mongoskin.CoreServer.disableServerAccounting)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.</span>enableServerAccounting ()](#apidoc.element.mongoskin.CoreServer.enableServerAccounting)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.</span>servers ()](#apidoc.element.mongoskin.CoreServer.servers)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.</span>super_ ()](#apidoc.element.mongoskin.CoreServer.super_)

#### [module mongoskin.CoreServer.prototype](#apidoc.module.mongoskin.CoreServer.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>auth (mechanism, db)](#apidoc.element.mongoskin.CoreServer.prototype.auth)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>command (ns, cmd, options, callback)](#apidoc.element.mongoskin.CoreServer.prototype.command)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>connect (options)](#apidoc.element.mongoskin.CoreServer.prototype.connect)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>connections ()](#apidoc.element.mongoskin.CoreServer.prototype.connections)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>cursor (ns, cmd, cursorOptions)](#apidoc.element.mongoskin.CoreServer.prototype.cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>destroy (options)](#apidoc.element.mongoskin.CoreServer.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>equals (server)](#apidoc.element.mongoskin.CoreServer.prototype.equals)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>getConnection ()](#apidoc.element.mongoskin.CoreServer.prototype.getConnection)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>getDescription ()](#apidoc.element.mongoskin.CoreServer.prototype.getDescription)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>getServer ()](#apidoc.element.mongoskin.CoreServer.prototype.getServer)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>insert (ns, ops, options, callback)](#apidoc.element.mongoskin.CoreServer.prototype.insert)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>isConnected ()](#apidoc.element.mongoskin.CoreServer.prototype.isConnected)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>isDestroyed ()](#apidoc.element.mongoskin.CoreServer.prototype.isDestroyed)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>lastIsMaster ()](#apidoc.element.mongoskin.CoreServer.prototype.lastIsMaster)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>logout (dbName, callback)](#apidoc.element.mongoskin.CoreServer.prototype.logout)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>remove (ns, ops, options, callback)](#apidoc.element.mongoskin.CoreServer.prototype.remove)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>unref ()](#apidoc.element.mongoskin.CoreServer.prototype.unref)
1.  [function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>update (ns, ops, options, callback)](#apidoc.element.mongoskin.CoreServer.prototype.update)
1.  string <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>parserType

#### [module mongoskin.Cursor](#apidoc.module.mongoskin.Cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Cursor ()](#apidoc.element.mongoskin.Cursor.Cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.</span>_bindGetter (propName)](#apidoc.element.mongoskin.Cursor._bindGetter)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.</span>_bindMethod (propName)](#apidoc.element.mongoskin.Cursor._bindMethod)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.</span>_bindSetter (propName)](#apidoc.element.mongoskin.Cursor._bindSetter)
1.  string <span class="apidocSignatureSpan">mongoskin.Cursor.</span>_class_name

#### [module mongoskin.Cursor.prototype](#apidoc.module.mongoskin.Cursor.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>_close (callback)](#apidoc.element.mongoskin.Cursor.prototype._close)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>_open (callback)](#apidoc.element.mongoskin.Cursor.prototype._open)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>addCursorFlag ()](#apidoc.element.mongoskin.Cursor.prototype.addCursorFlag)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>addListener ()](#apidoc.element.mongoskin.Cursor.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>addQueryModifier ()](#apidoc.element.mongoskin.Cursor.prototype.addQueryModifier)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>batchSize ()](#apidoc.element.mongoskin.Cursor.prototype.batchSize)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>bufferedCount ()](#apidoc.element.mongoskin.Cursor.prototype.bufferedCount)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>clone ()](#apidoc.element.mongoskin.Cursor.prototype.clone)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>close (callback)](#apidoc.element.mongoskin.Cursor.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>collation ()](#apidoc.element.mongoskin.Cursor.prototype.collation)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>comment ()](#apidoc.element.mongoskin.Cursor.prototype.comment)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>count ()](#apidoc.element.mongoskin.Cursor.prototype.count)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>cursorBatchSize ()](#apidoc.element.mongoskin.Cursor.prototype.cursorBatchSize)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>cursorLimit ()](#apidoc.element.mongoskin.Cursor.prototype.cursorLimit)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>cursorSkip ()](#apidoc.element.mongoskin.Cursor.prototype.cursorSkip)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>destroy ()](#apidoc.element.mongoskin.Cursor.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>each ()](#apidoc.element.mongoskin.Cursor.prototype.each)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>emit ()](#apidoc.element.mongoskin.Cursor.prototype.emit)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>eventNames ()](#apidoc.element.mongoskin.Cursor.prototype.eventNames)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>explain ()](#apidoc.element.mongoskin.Cursor.prototype.explain)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>filter ()](#apidoc.element.mongoskin.Cursor.prototype.filter)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>forEach ()](#apidoc.element.mongoskin.Cursor.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>getMaxListeners ()](#apidoc.element.mongoskin.Cursor.prototype.getMaxListeners)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>hasNext ()](#apidoc.element.mongoskin.Cursor.prototype.hasNext)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>hint ()](#apidoc.element.mongoskin.Cursor.prototype.hint)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isClosed ()](#apidoc.element.mongoskin.Cursor.prototype.isClosed)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isDead ()](#apidoc.element.mongoskin.Cursor.prototype.isDead)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isKilled ()](#apidoc.element.mongoskin.Cursor.prototype.isKilled)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isNotified ()](#apidoc.element.mongoskin.Cursor.prototype.isNotified)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isOpen ()](#apidoc.element.mongoskin.Cursor.prototype.isOpen)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isPaused ()](#apidoc.element.mongoskin.Cursor.prototype.isPaused)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>kill ()](#apidoc.element.mongoskin.Cursor.prototype.kill)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>limit ()](#apidoc.element.mongoskin.Cursor.prototype.limit)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>listenerCount ()](#apidoc.element.mongoskin.Cursor.prototype.listenerCount)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>listeners ()](#apidoc.element.mongoskin.Cursor.prototype.listeners)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>map ()](#apidoc.element.mongoskin.Cursor.prototype.map)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>max ()](#apidoc.element.mongoskin.Cursor.prototype.max)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>maxAwaitTimeMS ()](#apidoc.element.mongoskin.Cursor.prototype.maxAwaitTimeMS)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>maxScan ()](#apidoc.element.mongoskin.Cursor.prototype.maxScan)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>maxTimeMS ()](#apidoc.element.mongoskin.Cursor.prototype.maxTimeMS)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>maxTimeMs ()](#apidoc.element.mongoskin.Cursor.prototype.maxTimeMs)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>min ()](#apidoc.element.mongoskin.Cursor.prototype.min)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>next ()](#apidoc.element.mongoskin.Cursor.prototype.next)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>nextObject ()](#apidoc.element.mongoskin.Cursor.prototype.nextObject)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>on ()](#apidoc.element.mongoskin.Cursor.prototype.on)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>once ()](#apidoc.element.mongoskin.Cursor.prototype.once)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>open (callback)](#apidoc.element.mongoskin.Cursor.prototype.open)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>pause ()](#apidoc.element.mongoskin.Cursor.prototype.pause)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>pipe ()](#apidoc.element.mongoskin.Cursor.prototype.pipe)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>prependListener ()](#apidoc.element.mongoskin.Cursor.prototype.prependListener)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>prependOnceListener ()](#apidoc.element.mongoskin.Cursor.prototype.prependOnceListener)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>project ()](#apidoc.element.mongoskin.Cursor.prototype.project)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>push ()](#apidoc.element.mongoskin.Cursor.prototype.push)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>read ()](#apidoc.element.mongoskin.Cursor.prototype.read)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>readBufferedDocuments ()](#apidoc.element.mongoskin.Cursor.prototype.readBufferedDocuments)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>removeAllListeners ()](#apidoc.element.mongoskin.Cursor.prototype.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>removeListener ()](#apidoc.element.mongoskin.Cursor.prototype.removeListener)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>resume ()](#apidoc.element.mongoskin.Cursor.prototype.resume)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>returnKey ()](#apidoc.element.mongoskin.Cursor.prototype.returnKey)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>rewind ()](#apidoc.element.mongoskin.Cursor.prototype.rewind)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setCursorBatchSize ()](#apidoc.element.mongoskin.Cursor.prototype.setCursorBatchSize)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setCursorLimit ()](#apidoc.element.mongoskin.Cursor.prototype.setCursorLimit)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setCursorOption ()](#apidoc.element.mongoskin.Cursor.prototype.setCursorOption)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setCursorSkip ()](#apidoc.element.mongoskin.Cursor.prototype.setCursorSkip)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setEncoding ()](#apidoc.element.mongoskin.Cursor.prototype.setEncoding)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setMaxListeners ()](#apidoc.element.mongoskin.Cursor.prototype.setMaxListeners)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setReadPreference ()](#apidoc.element.mongoskin.Cursor.prototype.setReadPreference)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>showRecordId ()](#apidoc.element.mongoskin.Cursor.prototype.showRecordId)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>skip ()](#apidoc.element.mongoskin.Cursor.prototype.skip)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>snapshot ()](#apidoc.element.mongoskin.Cursor.prototype.snapshot)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>sort ()](#apidoc.element.mongoskin.Cursor.prototype.sort)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>stream ()](#apidoc.element.mongoskin.Cursor.prototype.stream)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>toArray ()](#apidoc.element.mongoskin.Cursor.prototype.toArray)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>unpipe ()](#apidoc.element.mongoskin.Cursor.prototype.unpipe)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>unshift ()](#apidoc.element.mongoskin.Cursor.prototype.unshift)
1.  [function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>wrap ()](#apidoc.element.mongoskin.Cursor.prototype.wrap)

#### [module mongoskin.DBRef](#apidoc.module.mongoskin.DBRef)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>DBRef (namespace, oid, db)](#apidoc.element.mongoskin.DBRef.DBRef)

#### [module mongoskin.DBRef.prototype](#apidoc.module.mongoskin.DBRef.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.DBRef.prototype.</span>toJSON ()](#apidoc.element.mongoskin.DBRef.prototype.toJSON)

#### [module mongoskin.Db](#apidoc.module.mongoskin.Db)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Db ()](#apidoc.element.mongoskin.Db.Db)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.</span>_bindGetter (propName)](#apidoc.element.mongoskin.Db._bindGetter)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.</span>_bindMethod (propName)](#apidoc.element.mongoskin.Db._bindMethod)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.</span>_bindSetter (propName)](#apidoc.element.mongoskin.Db._bindSetter)
1.  string <span class="apidocSignatureSpan">mongoskin.Db.</span>_class_name

#### [module mongoskin.Db.prototype](#apidoc.module.mongoskin.Db.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>_admin ()](#apidoc.element.mongoskin.Db.prototype._admin)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>_close (callback)](#apidoc.element.mongoskin.Db.prototype._close)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>_open (callback)](#apidoc.element.mongoskin.Db.prototype._open)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>addChild ()](#apidoc.element.mongoskin.Db.prototype.addChild)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>addListener ()](#apidoc.element.mongoskin.Db.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>addUser ()](#apidoc.element.mongoskin.Db.prototype.addUser)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>admin ()](#apidoc.element.mongoskin.Db.prototype.admin)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>authenticate ()](#apidoc.element.mongoskin.Db.prototype.authenticate)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>bind (name, options)](#apidoc.element.mongoskin.Db.prototype.bind)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>close (callback)](#apidoc.element.mongoskin.Db.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>collection (name, options)](#apidoc.element.mongoskin.Db.prototype.collection)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>collections ()](#apidoc.element.mongoskin.Db.prototype.collections)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>command ()](#apidoc.element.mongoskin.Db.prototype.command)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>createCollection ()](#apidoc.element.mongoskin.Db.prototype.createCollection)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>createIndex ()](#apidoc.element.mongoskin.Db.prototype.createIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>db ()](#apidoc.element.mongoskin.Db.prototype.db)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>dropCollection ()](#apidoc.element.mongoskin.Db.prototype.dropCollection)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>dropDatabase ()](#apidoc.element.mongoskin.Db.prototype.dropDatabase)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>emit ()](#apidoc.element.mongoskin.Db.prototype.emit)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>ensureIndex ()](#apidoc.element.mongoskin.Db.prototype.ensureIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>eval ()](#apidoc.element.mongoskin.Db.prototype.eval)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>eventNames ()](#apidoc.element.mongoskin.Db.prototype.eventNames)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>executeDbAdminCommand ()](#apidoc.element.mongoskin.Db.prototype.executeDbAdminCommand)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>getMaxListeners ()](#apidoc.element.mongoskin.Db.prototype.getMaxListeners)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>gridStore ()](#apidoc.element.mongoskin.Db.prototype.gridStore)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>indexInformation ()](#apidoc.element.mongoskin.Db.prototype.indexInformation)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>isOpen ()](#apidoc.element.mongoskin.Db.prototype.isOpen)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>listCollections ()](#apidoc.element.mongoskin.Db.prototype.listCollections)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>listenerCount ()](#apidoc.element.mongoskin.Db.prototype.listenerCount)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>listeners ()](#apidoc.element.mongoskin.Db.prototype.listeners)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>logout ()](#apidoc.element.mongoskin.Db.prototype.logout)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>on ()](#apidoc.element.mongoskin.Db.prototype.on)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>once ()](#apidoc.element.mongoskin.Db.prototype.once)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>open (callback)](#apidoc.element.mongoskin.Db.prototype.open)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>prependListener ()](#apidoc.element.mongoskin.Db.prototype.prependListener)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>prependOnceListener ()](#apidoc.element.mongoskin.Db.prototype.prependOnceListener)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>removeAllListeners ()](#apidoc.element.mongoskin.Db.prototype.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>removeListener ()](#apidoc.element.mongoskin.Db.prototype.removeListener)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>removeUser ()](#apidoc.element.mongoskin.Db.prototype.removeUser)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>renameCollection ()](#apidoc.element.mongoskin.Db.prototype.renameCollection)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>setMaxListeners ()](#apidoc.element.mongoskin.Db.prototype.setMaxListeners)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>stats ()](#apidoc.element.mongoskin.Db.prototype.stats)
1.  [function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>unref ()](#apidoc.element.mongoskin.Db.prototype.unref)

#### [module mongoskin.Decimal128](#apidoc.module.mongoskin.Decimal128)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Decimal128 (bytes)](#apidoc.element.mongoskin.Decimal128.Decimal128)
1.  [function <span class="apidocSignatureSpan">mongoskin.Decimal128.</span>fromString (string)](#apidoc.element.mongoskin.Decimal128.fromString)

#### [module mongoskin.Decimal128.prototype](#apidoc.module.mongoskin.Decimal128.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Decimal128.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Decimal128.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">mongoskin.Decimal128.prototype.</span>toString ()](#apidoc.element.mongoskin.Decimal128.prototype.toString)

#### [module mongoskin.Double](#apidoc.module.mongoskin.Double)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Double (value)](#apidoc.element.mongoskin.Double.Double)

#### [module mongoskin.Double.prototype](#apidoc.module.mongoskin.Double.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Double.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Double.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">mongoskin.Double.prototype.</span>valueOf ()](#apidoc.element.mongoskin.Double.prototype.valueOf)

#### [module mongoskin.GridFSBucket](#apidoc.module.mongoskin.GridFSBucket)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>GridFSBucket (db, options)](#apidoc.element.mongoskin.GridFSBucket.GridFSBucket)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.</span>super_ ()](#apidoc.element.mongoskin.GridFSBucket.super_)

#### [module mongoskin.GridFSBucket.prototype](#apidoc.module.mongoskin.GridFSBucket.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>delete (id, callback)](#apidoc.element.mongoskin.GridFSBucket.prototype.delete)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>drop (callback)](#apidoc.element.mongoskin.GridFSBucket.prototype.drop)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>find (filter, options)](#apidoc.element.mongoskin.GridFSBucket.prototype.find)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>openDownloadStream (id, options)](#apidoc.element.mongoskin.GridFSBucket.prototype.openDownloadStream)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>openDownloadStreamByName (filename, options)](#apidoc.element.mongoskin.GridFSBucket.prototype.openDownloadStreamByName)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>openUploadStream (filename, options)](#apidoc.element.mongoskin.GridFSBucket.prototype.openUploadStream)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>openUploadStreamWithId (id, filename, options)](#apidoc.element.mongoskin.GridFSBucket.prototype.openUploadStreamWithId)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>rename (id, filename, callback)](#apidoc.element.mongoskin.GridFSBucket.prototype.rename)

#### [module mongoskin.GridStore](#apidoc.module.mongoskin.GridStore)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>GridStore ()](#apidoc.element.mongoskin.GridStore.GridStore)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>_bindGetter (propName)](#apidoc.element.mongoskin.GridStore._bindGetter)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>_bindMethod (propName)](#apidoc.element.mongoskin.GridStore._bindMethod)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>_bindSetter (propName)](#apidoc.element.mongoskin.GridStore._bindSetter)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>exist (skindb)](#apidoc.element.mongoskin.GridStore.exist)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>list (skindb)](#apidoc.element.mongoskin.GridStore.list)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>read (skindb)](#apidoc.element.mongoskin.GridStore.read)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>readlines (skindb)](#apidoc.element.mongoskin.GridStore.readlines)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>unlink (skindb)](#apidoc.element.mongoskin.GridStore.unlink)
1.  string <span class="apidocSignatureSpan">mongoskin.GridStore.</span>_class_name

#### [module mongoskin.GridStore.prototype](#apidoc.module.mongoskin.GridStore.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>_close (callback)](#apidoc.element.mongoskin.GridStore.prototype._close)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>_open (callback)](#apidoc.element.mongoskin.GridStore.prototype._open)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>chunkCollection ()](#apidoc.element.mongoskin.GridStore.prototype.chunkCollection)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>close (callback)](#apidoc.element.mongoskin.GridStore.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>collection ()](#apidoc.element.mongoskin.GridStore.prototype.collection)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>destroy ()](#apidoc.element.mongoskin.GridStore.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>eof ()](#apidoc.element.mongoskin.GridStore.prototype.eof)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>getc ()](#apidoc.element.mongoskin.GridStore.prototype.getc)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>isOpen ()](#apidoc.element.mongoskin.GridStore.prototype.isOpen)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>open (callback)](#apidoc.element.mongoskin.GridStore.prototype.open)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>puts ()](#apidoc.element.mongoskin.GridStore.prototype.puts)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>read ()](#apidoc.element.mongoskin.GridStore.prototype.read)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>readlines ()](#apidoc.element.mongoskin.GridStore.prototype.readlines)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>rewind ()](#apidoc.element.mongoskin.GridStore.prototype.rewind)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>seek ()](#apidoc.element.mongoskin.GridStore.prototype.seek)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>stream ()](#apidoc.element.mongoskin.GridStore.prototype.stream)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>tell ()](#apidoc.element.mongoskin.GridStore.prototype.tell)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>unlink ()](#apidoc.element.mongoskin.GridStore.prototype.unlink)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>write ()](#apidoc.element.mongoskin.GridStore.prototype.write)
1.  [function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>writeFile ()](#apidoc.element.mongoskin.GridStore.prototype.writeFile)

#### [module mongoskin.Int32](#apidoc.module.mongoskin.Int32)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Int32 (value)](#apidoc.element.mongoskin.Int32.Int32)

#### [module mongoskin.Int32.prototype](#apidoc.module.mongoskin.Int32.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Int32.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Int32.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">mongoskin.Int32.prototype.</span>valueOf ()](#apidoc.element.mongoskin.Int32.prototype.valueOf)

#### [module mongoskin.Logger](#apidoc.module.mongoskin.Logger)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Logger (className, options)](#apidoc.element.mongoskin.Logger.Logger)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.</span>currentLogger ()](#apidoc.element.mongoskin.Logger.currentLogger)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.</span>filter (type, values)](#apidoc.element.mongoskin.Logger.filter)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.</span>reset ()](#apidoc.element.mongoskin.Logger.reset)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.</span>setCurrentLogger (logger)](#apidoc.element.mongoskin.Logger.setCurrentLogger)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.</span>setLevel (_level)](#apidoc.element.mongoskin.Logger.setLevel)

#### [module mongoskin.Logger.prototype](#apidoc.module.mongoskin.Logger.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>debug (message, object)](#apidoc.element.mongoskin.Logger.prototype.debug)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>error (message, object)](#apidoc.element.mongoskin.Logger.prototype.error)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>info (message, object)](#apidoc.element.mongoskin.Logger.prototype.info)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>isDebug ()](#apidoc.element.mongoskin.Logger.prototype.isDebug)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>isError ()](#apidoc.element.mongoskin.Logger.prototype.isError)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>isInfo ()](#apidoc.element.mongoskin.Logger.prototype.isInfo)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>isWarn ()](#apidoc.element.mongoskin.Logger.prototype.isWarn)
1.  [function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>warn (message, object)](#apidoc.element.mongoskin.Logger.prototype.warn)

#### [module mongoskin.Long](#apidoc.module.mongoskin.Long)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Long (low, high)](#apidoc.element.mongoskin.Long.Long)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.</span>fromBits (lowBits, highBits)](#apidoc.element.mongoskin.Long.fromBits)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.</span>fromInt (value)](#apidoc.element.mongoskin.Long.fromInt)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.</span>fromNumber (value)](#apidoc.element.mongoskin.Long.fromNumber)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.</span>fromString (str, opt_radix)](#apidoc.element.mongoskin.Long.fromString)
1.  number <span class="apidocSignatureSpan">mongoskin.Long.</span>TWO_PWR_16_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Long.</span>TWO_PWR_24_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Long.</span>TWO_PWR_31_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Long.</span>TWO_PWR_32_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Long.</span>TWO_PWR_48_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Long.</span>TWO_PWR_63_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Long.</span>TWO_PWR_64_DBL_
1.  object <span class="apidocSignatureSpan">mongoskin.Long.</span>INT_CACHE_
1.  object <span class="apidocSignatureSpan">mongoskin.Long.</span>MAX_VALUE
1.  object <span class="apidocSignatureSpan">mongoskin.Long.</span>MIN_VALUE
1.  object <span class="apidocSignatureSpan">mongoskin.Long.</span>NEG_ONE
1.  object <span class="apidocSignatureSpan">mongoskin.Long.</span>ONE
1.  object <span class="apidocSignatureSpan">mongoskin.Long.</span>TWO_PWR_24_
1.  object <span class="apidocSignatureSpan">mongoskin.Long.</span>ZERO

#### [module mongoskin.Long.prototype](#apidoc.module.mongoskin.Long.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>add (other)](#apidoc.element.mongoskin.Long.prototype.add)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>and (other)](#apidoc.element.mongoskin.Long.prototype.and)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>compare (other)](#apidoc.element.mongoskin.Long.prototype.compare)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>div (other)](#apidoc.element.mongoskin.Long.prototype.div)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>equals (other)](#apidoc.element.mongoskin.Long.prototype.equals)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>getHighBits ()](#apidoc.element.mongoskin.Long.prototype.getHighBits)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>getLowBits ()](#apidoc.element.mongoskin.Long.prototype.getLowBits)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>getLowBitsUnsigned ()](#apidoc.element.mongoskin.Long.prototype.getLowBitsUnsigned)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>getNumBitsAbs ()](#apidoc.element.mongoskin.Long.prototype.getNumBitsAbs)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>greaterThan (other)](#apidoc.element.mongoskin.Long.prototype.greaterThan)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>greaterThanOrEqual (other)](#apidoc.element.mongoskin.Long.prototype.greaterThanOrEqual)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>isNegative ()](#apidoc.element.mongoskin.Long.prototype.isNegative)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>isOdd ()](#apidoc.element.mongoskin.Long.prototype.isOdd)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>isZero ()](#apidoc.element.mongoskin.Long.prototype.isZero)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>lessThan (other)](#apidoc.element.mongoskin.Long.prototype.lessThan)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>lessThanOrEqual (other)](#apidoc.element.mongoskin.Long.prototype.lessThanOrEqual)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>modulo (other)](#apidoc.element.mongoskin.Long.prototype.modulo)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>multiply (other)](#apidoc.element.mongoskin.Long.prototype.multiply)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>negate ()](#apidoc.element.mongoskin.Long.prototype.negate)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>not ()](#apidoc.element.mongoskin.Long.prototype.not)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>notEquals (other)](#apidoc.element.mongoskin.Long.prototype.notEquals)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>or (other)](#apidoc.element.mongoskin.Long.prototype.or)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>shiftLeft (numBits)](#apidoc.element.mongoskin.Long.prototype.shiftLeft)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>shiftRight (numBits)](#apidoc.element.mongoskin.Long.prototype.shiftRight)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>shiftRightUnsigned (numBits)](#apidoc.element.mongoskin.Long.prototype.shiftRightUnsigned)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>subtract (other)](#apidoc.element.mongoskin.Long.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>toInt ()](#apidoc.element.mongoskin.Long.prototype.toInt)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Long.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>toNumber ()](#apidoc.element.mongoskin.Long.prototype.toNumber)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>toString (opt_radix)](#apidoc.element.mongoskin.Long.prototype.toString)
1.  [function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>xor (other)](#apidoc.element.mongoskin.Long.prototype.xor)

#### [module mongoskin.Map](#apidoc.module.mongoskin.Map)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Map ()](#apidoc.element.mongoskin.Map.Map)

#### [module mongoskin.MaxKey](#apidoc.module.mongoskin.MaxKey)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>MaxKey ()](#apidoc.element.mongoskin.MaxKey.MaxKey)

#### [module mongoskin.MinKey](#apidoc.module.mongoskin.MinKey)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>MinKey ()](#apidoc.element.mongoskin.MinKey.MinKey)

#### [module mongoskin.MongoClient](#apidoc.module.mongoskin.MongoClient)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>MongoClient ()](#apidoc.element.mongoskin.MongoClient.MongoClient)
1.  [function <span class="apidocSignatureSpan">mongoskin.MongoClient.</span>_bindGetter (propName)](#apidoc.element.mongoskin.MongoClient._bindGetter)
1.  [function <span class="apidocSignatureSpan">mongoskin.MongoClient.</span>_bindMethod (propName)](#apidoc.element.mongoskin.MongoClient._bindMethod)
1.  [function <span class="apidocSignatureSpan">mongoskin.MongoClient.</span>_bindSetter (propName)](#apidoc.element.mongoskin.MongoClient._bindSetter)
1.  [function <span class="apidocSignatureSpan">mongoskin.MongoClient.</span>connect ()](#apidoc.element.mongoskin.MongoClient.connect)
1.  string <span class="apidocSignatureSpan">mongoskin.MongoClient.</span>_class_name

#### [module mongoskin.MongoClient.prototype](#apidoc.module.mongoskin.MongoClient.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.MongoClient.prototype.</span>_close (callback)](#apidoc.element.mongoskin.MongoClient.prototype._close)
1.  [function <span class="apidocSignatureSpan">mongoskin.MongoClient.prototype.</span>close (callback)](#apidoc.element.mongoskin.MongoClient.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.MongoClient.prototype.</span>isOpen ()](#apidoc.element.mongoskin.MongoClient.prototype.isOpen)
1.  [function <span class="apidocSignatureSpan">mongoskin.MongoClient.prototype.</span>open (callback)](#apidoc.element.mongoskin.MongoClient.prototype.open)

#### [module mongoskin.MongoError](#apidoc.module.mongoskin.MongoError)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>MongoError (message)](#apidoc.element.mongoskin.MongoError.MongoError)
1.  [function <span class="apidocSignatureSpan">mongoskin.MongoError.</span>create (options)](#apidoc.element.mongoskin.MongoError.create)

#### [module mongoskin.Mongos](#apidoc.module.mongoskin.Mongos)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Mongos (servers, options)](#apidoc.element.mongoskin.Mongos.Mongos)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.</span>super_ ()](#apidoc.element.mongoskin.Mongos.super_)
1.  object <span class="apidocSignatureSpan">mongoskin.Mongos.</span>define

#### [module mongoskin.Mongos.define](#apidoc.module.mongoskin.Mongos.define)
1.  boolean <span class="apidocSignatureSpan">mongoskin.Mongos.define.</span>stream
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.define.</span>object (servers, options)](#apidoc.element.mongoskin.Mongos.define.object)
1.  object <span class="apidocSignatureSpan">mongoskin.Mongos.define.</span>instrumentations
1.  string <span class="apidocSignatureSpan">mongoskin.Mongos.define.</span>name

#### [module mongoskin.Mongos.prototype](#apidoc.module.mongoskin.Mongos.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>auth ()](#apidoc.element.mongoskin.Mongos.prototype.auth)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>capabilities ()](#apidoc.element.mongoskin.Mongos.prototype.capabilities)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>close (forceClosed)](#apidoc.element.mongoskin.Mongos.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>command (ns, cmd, options, callback)](#apidoc.element.mongoskin.Mongos.prototype.command)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>connect (db, _options, callback)](#apidoc.element.mongoskin.Mongos.prototype.connect)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>connections ()](#apidoc.element.mongoskin.Mongos.prototype.connections)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>cursor (ns, cmd, options)](#apidoc.element.mongoskin.Mongos.prototype.cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>insert (ns, ops, options, callback)](#apidoc.element.mongoskin.Mongos.prototype.insert)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>isConnected ()](#apidoc.element.mongoskin.Mongos.prototype.isConnected)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>isDestroyed ()](#apidoc.element.mongoskin.Mongos.prototype.isDestroyed)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>lastIsMaster ()](#apidoc.element.mongoskin.Mongos.prototype.lastIsMaster)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>logout ()](#apidoc.element.mongoskin.Mongos.prototype.logout)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>remove (ns, ops, options, callback)](#apidoc.element.mongoskin.Mongos.prototype.remove)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>unref ()](#apidoc.element.mongoskin.Mongos.prototype.unref)
1.  [function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>update (ns, ops, options, callback)](#apidoc.element.mongoskin.Mongos.prototype.update)

#### [module mongoskin.ObjectID](#apidoc.module.mongoskin.ObjectID)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>ObjectID (id)](#apidoc.element.mongoskin.ObjectID.ObjectID)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.</span>ObjectId (id)](#apidoc.element.mongoskin.ObjectID.ObjectId)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.</span>createFromHexString (string)](#apidoc.element.mongoskin.ObjectID.createFromHexString)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.</span>createFromTime (time)](#apidoc.element.mongoskin.ObjectID.createFromTime)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.</span>createPk ()](#apidoc.element.mongoskin.ObjectID.createPk)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.</span>isValid (id)](#apidoc.element.mongoskin.ObjectID.isValid)
1.  number <span class="apidocSignatureSpan">mongoskin.ObjectID.</span>index

#### [module mongoskin.ObjectID.prototype](#apidoc.module.mongoskin.ObjectID.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>equals (otherId)](#apidoc.element.mongoskin.ObjectID.prototype.equals)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>generate (time)](#apidoc.element.mongoskin.ObjectID.prototype.generate)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>getInc ()](#apidoc.element.mongoskin.ObjectID.prototype.getInc)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>getTimestamp ()](#apidoc.element.mongoskin.ObjectID.prototype.getTimestamp)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>get_inc ()](#apidoc.element.mongoskin.ObjectID.prototype.get_inc)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>inspect (format)](#apidoc.element.mongoskin.ObjectID.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>toHexString ()](#apidoc.element.mongoskin.ObjectID.prototype.toHexString)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>toJSON ()](#apidoc.element.mongoskin.ObjectID.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>toString (format)](#apidoc.element.mongoskin.ObjectID.prototype.toString)

#### [module mongoskin.ReadPreference](#apidoc.module.mongoskin.ReadPreference)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>ReadPreference (mode, tags, options)](#apidoc.element.mongoskin.ReadPreference.ReadPreference)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReadPreference.</span>isValid (_mode)](#apidoc.element.mongoskin.ReadPreference.isValid)
1.  string <span class="apidocSignatureSpan">mongoskin.ReadPreference.</span>NEAREST
1.  string <span class="apidocSignatureSpan">mongoskin.ReadPreference.</span>PRIMARY
1.  string <span class="apidocSignatureSpan">mongoskin.ReadPreference.</span>PRIMARY_PREFERRED
1.  string <span class="apidocSignatureSpan">mongoskin.ReadPreference.</span>SECONDARY
1.  string <span class="apidocSignatureSpan">mongoskin.ReadPreference.</span>SECONDARY_PREFERRED

#### [module mongoskin.ReadPreference.prototype](#apidoc.module.mongoskin.ReadPreference.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReadPreference.prototype.</span>isValid (mode)](#apidoc.element.mongoskin.ReadPreference.prototype.isValid)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReadPreference.prototype.</span>toJSON ()](#apidoc.element.mongoskin.ReadPreference.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReadPreference.prototype.</span>toObject ()](#apidoc.element.mongoskin.ReadPreference.prototype.toObject)

#### [module mongoskin.ReplSet](#apidoc.module.mongoskin.ReplSet)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>ReplSet (servers, options)](#apidoc.element.mongoskin.ReplSet.ReplSet)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.</span>super_ ()](#apidoc.element.mongoskin.ReplSet.super_)
1.  object <span class="apidocSignatureSpan">mongoskin.ReplSet.</span>define

#### [module mongoskin.ReplSet.define](#apidoc.module.mongoskin.ReplSet.define)
1.  boolean <span class="apidocSignatureSpan">mongoskin.ReplSet.define.</span>stream
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.define.</span>object (servers, options)](#apidoc.element.mongoskin.ReplSet.define.object)
1.  object <span class="apidocSignatureSpan">mongoskin.ReplSet.define.</span>instrumentations
1.  string <span class="apidocSignatureSpan">mongoskin.ReplSet.define.</span>name

#### [module mongoskin.ReplSet.prototype](#apidoc.module.mongoskin.ReplSet.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>auth ()](#apidoc.element.mongoskin.ReplSet.prototype.auth)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>capabilities ()](#apidoc.element.mongoskin.ReplSet.prototype.capabilities)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>close (forceClosed)](#apidoc.element.mongoskin.ReplSet.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>command (ns, cmd, options, callback)](#apidoc.element.mongoskin.ReplSet.prototype.command)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>connect (db, _options, callback)](#apidoc.element.mongoskin.ReplSet.prototype.connect)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>connections ()](#apidoc.element.mongoskin.ReplSet.prototype.connections)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>cursor (ns, cmd, options)](#apidoc.element.mongoskin.ReplSet.prototype.cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>insert (ns, ops, options, callback)](#apidoc.element.mongoskin.ReplSet.prototype.insert)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>isConnected (options)](#apidoc.element.mongoskin.ReplSet.prototype.isConnected)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>isDestroyed ()](#apidoc.element.mongoskin.ReplSet.prototype.isDestroyed)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>lastIsMaster ()](#apidoc.element.mongoskin.ReplSet.prototype.lastIsMaster)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>logout ()](#apidoc.element.mongoskin.ReplSet.prototype.logout)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>remove (ns, ops, options, callback)](#apidoc.element.mongoskin.ReplSet.prototype.remove)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>unref ()](#apidoc.element.mongoskin.ReplSet.prototype.unref)
1.  [function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>update (ns, ops, options, callback)](#apidoc.element.mongoskin.ReplSet.prototype.update)

#### [module mongoskin.Server](#apidoc.module.mongoskin.Server)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Server (host, port, options)](#apidoc.element.mongoskin.Server.Server)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.</span>super_ ()](#apidoc.element.mongoskin.Server.super_)
1.  object <span class="apidocSignatureSpan">mongoskin.Server.</span>define

#### [module mongoskin.Server.define](#apidoc.module.mongoskin.Server.define)
1.  boolean <span class="apidocSignatureSpan">mongoskin.Server.define.</span>stream
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.define.</span>object (host, port, options)](#apidoc.element.mongoskin.Server.define.object)
1.  object <span class="apidocSignatureSpan">mongoskin.Server.define.</span>instrumentations
1.  string <span class="apidocSignatureSpan">mongoskin.Server.define.</span>name

#### [module mongoskin.Server.prototype](#apidoc.module.mongoskin.Server.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>auth ()](#apidoc.element.mongoskin.Server.prototype.auth)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>capabilities ()](#apidoc.element.mongoskin.Server.prototype.capabilities)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>close (forceClosed)](#apidoc.element.mongoskin.Server.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>command (ns, cmd, options, callback)](#apidoc.element.mongoskin.Server.prototype.command)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>connect (db, _options, callback)](#apidoc.element.mongoskin.Server.prototype.connect)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>connections ()](#apidoc.element.mongoskin.Server.prototype.connections)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>cursor (ns, cmd, options)](#apidoc.element.mongoskin.Server.prototype.cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>insert (ns, ops, options, callback)](#apidoc.element.mongoskin.Server.prototype.insert)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>isConnected ()](#apidoc.element.mongoskin.Server.prototype.isConnected)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>isDestroyed ()](#apidoc.element.mongoskin.Server.prototype.isDestroyed)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>lastIsMaster ()](#apidoc.element.mongoskin.Server.prototype.lastIsMaster)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>logout ()](#apidoc.element.mongoskin.Server.prototype.logout)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>remove (ns, ops, options, callback)](#apidoc.element.mongoskin.Server.prototype.remove)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>unref ()](#apidoc.element.mongoskin.Server.prototype.unref)
1.  [function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>update (ns, ops, options, callback)](#apidoc.element.mongoskin.Server.prototype.update)

#### [module mongoskin.Symbol](#apidoc.module.mongoskin.Symbol)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Symbol (value)](#apidoc.element.mongoskin.Symbol.Symbol)

#### [module mongoskin.Symbol.prototype](#apidoc.module.mongoskin.Symbol.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Symbol.prototype.</span>inspect ()](#apidoc.element.mongoskin.Symbol.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">mongoskin.Symbol.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Symbol.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">mongoskin.Symbol.prototype.</span>toString ()](#apidoc.element.mongoskin.Symbol.prototype.toString)
1.  [function <span class="apidocSignatureSpan">mongoskin.Symbol.prototype.</span>valueOf ()](#apidoc.element.mongoskin.Symbol.prototype.valueOf)

#### [module mongoskin.Timestamp](#apidoc.module.mongoskin.Timestamp)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>Timestamp (low, high)](#apidoc.element.mongoskin.Timestamp.Timestamp)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>fromBits (lowBits, highBits)](#apidoc.element.mongoskin.Timestamp.fromBits)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>fromInt (value)](#apidoc.element.mongoskin.Timestamp.fromInt)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>fromNumber (value)](#apidoc.element.mongoskin.Timestamp.fromNumber)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>fromString (str, opt_radix)](#apidoc.element.mongoskin.Timestamp.fromString)
1.  number <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>TWO_PWR_16_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>TWO_PWR_24_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>TWO_PWR_31_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>TWO_PWR_32_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>TWO_PWR_48_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>TWO_PWR_63_DBL_
1.  number <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>TWO_PWR_64_DBL_
1.  object <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>INT_CACHE_
1.  object <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>MAX_VALUE
1.  object <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>MIN_VALUE
1.  object <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>NEG_ONE
1.  object <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>ONE
1.  object <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>TWO_PWR_24_
1.  object <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>ZERO

#### [module mongoskin.Timestamp.prototype](#apidoc.module.mongoskin.Timestamp.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>add (other)](#apidoc.element.mongoskin.Timestamp.prototype.add)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>and (other)](#apidoc.element.mongoskin.Timestamp.prototype.and)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>compare (other)](#apidoc.element.mongoskin.Timestamp.prototype.compare)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>div (other)](#apidoc.element.mongoskin.Timestamp.prototype.div)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>equals (other)](#apidoc.element.mongoskin.Timestamp.prototype.equals)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>getHighBits ()](#apidoc.element.mongoskin.Timestamp.prototype.getHighBits)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>getLowBits ()](#apidoc.element.mongoskin.Timestamp.prototype.getLowBits)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>getLowBitsUnsigned ()](#apidoc.element.mongoskin.Timestamp.prototype.getLowBitsUnsigned)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>getNumBitsAbs ()](#apidoc.element.mongoskin.Timestamp.prototype.getNumBitsAbs)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>greaterThan (other)](#apidoc.element.mongoskin.Timestamp.prototype.greaterThan)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>greaterThanOrEqual (other)](#apidoc.element.mongoskin.Timestamp.prototype.greaterThanOrEqual)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>isNegative ()](#apidoc.element.mongoskin.Timestamp.prototype.isNegative)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>isOdd ()](#apidoc.element.mongoskin.Timestamp.prototype.isOdd)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>isZero ()](#apidoc.element.mongoskin.Timestamp.prototype.isZero)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>lessThan (other)](#apidoc.element.mongoskin.Timestamp.prototype.lessThan)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>lessThanOrEqual (other)](#apidoc.element.mongoskin.Timestamp.prototype.lessThanOrEqual)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>modulo (other)](#apidoc.element.mongoskin.Timestamp.prototype.modulo)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>multiply (other)](#apidoc.element.mongoskin.Timestamp.prototype.multiply)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>negate ()](#apidoc.element.mongoskin.Timestamp.prototype.negate)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>not ()](#apidoc.element.mongoskin.Timestamp.prototype.not)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>notEquals (other)](#apidoc.element.mongoskin.Timestamp.prototype.notEquals)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>or (other)](#apidoc.element.mongoskin.Timestamp.prototype.or)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>shiftLeft (numBits)](#apidoc.element.mongoskin.Timestamp.prototype.shiftLeft)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>shiftRight (numBits)](#apidoc.element.mongoskin.Timestamp.prototype.shiftRight)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>shiftRightUnsigned (numBits)](#apidoc.element.mongoskin.Timestamp.prototype.shiftRightUnsigned)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>subtract (other)](#apidoc.element.mongoskin.Timestamp.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>toInt ()](#apidoc.element.mongoskin.Timestamp.prototype.toInt)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Timestamp.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>toNumber ()](#apidoc.element.mongoskin.Timestamp.prototype.toNumber)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>toString (opt_radix)](#apidoc.element.mongoskin.Timestamp.prototype.toString)
1.  [function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>xor (other)](#apidoc.element.mongoskin.Timestamp.prototype.xor)

#### [module mongoskin.admin](#apidoc.module.mongoskin.admin)
1.  [function <span class="apidocSignatureSpan">mongoskin.admin.</span>SkinAdmin ()](#apidoc.element.mongoskin.admin.SkinAdmin)

#### [module mongoskin.collection](#apidoc.module.mongoskin.collection)
1.  [function <span class="apidocSignatureSpan">mongoskin.collection.</span>SkinCollection ()](#apidoc.element.mongoskin.collection.SkinCollection)

#### [module mongoskin.connect](#apidoc.module.mongoskin.connect)
1.  [function <span class="apidocSignatureSpan">mongoskin.</span>connect (url, options, callback)](#apidoc.element.mongoskin.connect.connect)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Admin (db, topology, promiseLibrary)](#apidoc.element.mongoskin.connect.Admin)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>BSONRegExp (pattern, options)](#apidoc.element.mongoskin.connect.BSONRegExp)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Binary (buffer, subType)](#apidoc.element.mongoskin.connect.Binary)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Chunk (file, mongoObject, writeConcern)](#apidoc.element.mongoskin.connect.Chunk)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Code (code, scope)](#apidoc.element.mongoskin.connect.Code)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Collection (db, topology, dbName, name, pkFactory, options)](#apidoc.element.mongoskin.connect.Collection)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>CoreConnection (messageHandler, options)](#apidoc.element.mongoskin.connect.CoreConnection)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>CoreServer (options)](#apidoc.element.mongoskin.connect.CoreServer)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Cursor (bson, ns, cmd, options, topology, topologyOptions)](#apidoc.element.mongoskin.connect.Cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>DBRef (namespace, oid, db)](#apidoc.element.mongoskin.connect.DBRef)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Db (databaseName, topology, options)](#apidoc.element.mongoskin.connect.Db)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Decimal128 (bytes)](#apidoc.element.mongoskin.connect.Decimal128)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Double (value)](#apidoc.element.mongoskin.connect.Double)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>GridFSBucket (db, options)](#apidoc.element.mongoskin.connect.GridFSBucket)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>GridStore (db, id, filename, mode, options)](#apidoc.element.mongoskin.connect.GridStore)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Int32 (value)](#apidoc.element.mongoskin.connect.Int32)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Logger (className, options)](#apidoc.element.mongoskin.connect.Logger)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Long (low, high)](#apidoc.element.mongoskin.connect.Long)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Map ()](#apidoc.element.mongoskin.connect.Map)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>MaxKey ()](#apidoc.element.mongoskin.connect.MaxKey)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>MinKey ()](#apidoc.element.mongoskin.connect.MinKey)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>MongoClient ()](#apidoc.element.mongoskin.connect.MongoClient)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>MongoError (message)](#apidoc.element.mongoskin.connect.MongoError)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Mongos (servers, options)](#apidoc.element.mongoskin.connect.Mongos)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>ObjectID (id)](#apidoc.element.mongoskin.connect.ObjectID)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>ObjectId (id)](#apidoc.element.mongoskin.connect.ObjectId)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>ReadPreference (mode, tags, options)](#apidoc.element.mongoskin.connect.ReadPreference)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>ReplSet (servers, options)](#apidoc.element.mongoskin.connect.ReplSet)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Server (host, port, options)](#apidoc.element.mongoskin.connect.Server)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Symbol (value)](#apidoc.element.mongoskin.connect.Symbol)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Timestamp (low, high)](#apidoc.element.mongoskin.connect.Timestamp)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>instrument (options, callback)](#apidoc.element.mongoskin.connect.instrument)

#### [module mongoskin.connect.Admin](#apidoc.module.mongoskin.connect.Admin)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Admin (db, topology, promiseLibrary)](#apidoc.element.mongoskin.connect.Admin.Admin)
1.  object <span class="apidocSignatureSpan">mongoskin.connect.Admin.</span>define

#### [module mongoskin.connect.Admin.prototype](#apidoc.module.mongoskin.connect.Admin.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>addUser (username, password, options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.addUser)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>authenticate (username, password, options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.authenticate)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>buildInfo (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.buildInfo)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>command (command, options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.command)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>listDatabases (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.listDatabases)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>logout (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.logout)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>ping (options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.ping)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>profilingInfo (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.profilingInfo)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>profilingLevel (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.profilingLevel)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>removeUser (username, options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.removeUser)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>replSetGetStatus (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.replSetGetStatus)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>serverInfo (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.serverInfo)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>serverStatus (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.serverStatus)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>setProfilingLevel (level, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.setProfilingLevel)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>validateCollection (collectionName, options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.validateCollection)

#### [module mongoskin.connect.Collection](#apidoc.module.mongoskin.connect.Collection)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Collection (db, topology, dbName, name, pkFactory, options)](#apidoc.element.mongoskin.connect.Collection.Collection)
1.  object <span class="apidocSignatureSpan">mongoskin.connect.Collection.</span>define

#### [module mongoskin.connect.Collection.prototype](#apidoc.module.mongoskin.connect.Collection.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>aggregate (pipeline, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.aggregate)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>bulkWrite (operations, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.bulkWrite)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>count (query, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.count)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>createIndex (fieldOrSpec, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.createIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>createIndexes (indexSpecs, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.createIndexes)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>deleteMany (filter, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.deleteMany)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>deleteOne (filter, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.deleteOne)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>distinct (key, query, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.distinct)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>drop (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.drop)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>dropAllIndexes (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.dropAllIndexes)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>dropIndex (indexName, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.dropIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>dropIndexes (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.dropIndexes)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>ensureIndex (fieldOrSpec, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.ensureIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>find ()](#apidoc.element.mongoskin.connect.Collection.prototype.find)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findAndModify (query, sort, doc, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.findAndModify)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findAndRemove (query, sort, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.findAndRemove)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findOne ()](#apidoc.element.mongoskin.connect.Collection.prototype.findOne)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findOneAndDelete (filter, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.findOneAndDelete)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findOneAndReplace (filter, replacement, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.findOneAndReplace)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findOneAndUpdate (filter, update, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.findOneAndUpdate)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>geoHaystackSearch (x, y, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.geoHaystackSearch)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>geoNear (x, y, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.geoNear)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>group (keys, condition, initial, reduce, finalize, command, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.group)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>indexExists (indexes, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.indexExists)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>indexInformation (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.indexInformation)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>indexes (callback)](#apidoc.element.mongoskin.connect.Collection.prototype.indexes)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>initializeOrderedBulkOp (options)](#apidoc.element.mongoskin.connect.Collection.prototype.initializeOrderedBulkOp)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>initializeUnorderedBulkOp (options)](#apidoc.element.mongoskin.connect.Collection.prototype.initializeUnorderedBulkOp)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>insert (docs, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.insert)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>insertMany (docs, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.insertMany)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>insertOne (doc, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.insertOne)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>isCapped (callback)](#apidoc.element.mongoskin.connect.Collection.prototype.isCapped)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>listIndexes (options)](#apidoc.element.mongoskin.connect.Collection.prototype.listIndexes)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>mapReduce (map, reduce, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.mapReduce)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>options (callback)](#apidoc.element.mongoskin.connect.Collection.prototype.options)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>parallelCollectionScan (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.parallelCollectionScan)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>reIndex (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.reIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>remove (selector, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.remove)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>removeMany (filter, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.removeMany)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>removeOne (filter, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.removeOne)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>rename (newName, opt, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.rename)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>replaceOne (filter, doc, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.replaceOne)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>save (doc, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.save)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>stats (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.stats)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>update (selector, document, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.update)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>updateMany (filter, update, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.updateMany)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>updateOne (filter, update, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.updateOne)

#### [module mongoskin.connect.Cursor](#apidoc.module.mongoskin.connect.Cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Cursor (bson, ns, cmd, options, topology, topologyOptions)](#apidoc.element.mongoskin.connect.Cursor.Cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.</span>super_ (options)](#apidoc.element.mongoskin.connect.Cursor.super_)
1.  number <span class="apidocSignatureSpan">mongoskin.connect.Cursor.</span>CLOSED
1.  number <span class="apidocSignatureSpan">mongoskin.connect.Cursor.</span>GET_MORE
1.  number <span class="apidocSignatureSpan">mongoskin.connect.Cursor.</span>INIT
1.  number <span class="apidocSignatureSpan">mongoskin.connect.Cursor.</span>OPEN
1.  object <span class="apidocSignatureSpan">mongoskin.connect.Cursor.</span>define

#### [module mongoskin.connect.Cursor.prototype](#apidoc.module.mongoskin.connect.Cursor.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>_find (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype._find)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>_getmore (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype._getmore)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>_killcursor (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype._killcursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>_next (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype._next)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>_read ()](#apidoc.element.mongoskin.connect.Cursor.prototype._read)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>addCursorFlag (flag, value)](#apidoc.element.mongoskin.connect.Cursor.prototype.addCursorFlag)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>addQueryModifier (name, value)](#apidoc.element.mongoskin.connect.Cursor.prototype.addQueryModifier)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>batchSize (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.batchSize)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>bufferedCount ()](#apidoc.element.mongoskin.connect.Cursor.prototype.bufferedCount)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>clone ()](#apidoc.element.mongoskin.connect.Cursor.prototype.clone)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>close (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>collation (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.collation)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>comment (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.comment)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>count (applySkipLimit, opts, callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.count)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>cursorBatchSize ()](#apidoc.element.mongoskin.connect.Cursor.prototype.cursorBatchSize)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>cursorLimit ()](#apidoc.element.mongoskin.connect.Cursor.prototype.cursorLimit)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>cursorSkip ()](#apidoc.element.mongoskin.connect.Cursor.prototype.cursorSkip)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>destroy (err)](#apidoc.element.mongoskin.connect.Cursor.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>each (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.each)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>explain (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.explain)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>filter (filter)](#apidoc.element.mongoskin.connect.Cursor.prototype.filter)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>forEach (iterator, callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>hasNext (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.hasNext)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>hint (hint)](#apidoc.element.mongoskin.connect.Cursor.prototype.hint)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>isClosed ()](#apidoc.element.mongoskin.connect.Cursor.prototype.isClosed)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>isDead ()](#apidoc.element.mongoskin.connect.Cursor.prototype.isDead)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>isKilled ()](#apidoc.element.mongoskin.connect.Cursor.prototype.isKilled)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>isNotified ()](#apidoc.element.mongoskin.connect.Cursor.prototype.isNotified)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>kill (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.kill)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>limit (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.limit)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>map (transform)](#apidoc.element.mongoskin.connect.Cursor.prototype.map)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>max (max)](#apidoc.element.mongoskin.connect.Cursor.prototype.max)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>maxAwaitTimeMS (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.maxAwaitTimeMS)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>maxScan (maxScan)](#apidoc.element.mongoskin.connect.Cursor.prototype.maxScan)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>maxTimeMS (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.maxTimeMS)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>maxTimeMs (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.maxTimeMs)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>min (min)](#apidoc.element.mongoskin.connect.Cursor.prototype.min)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>next (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.next)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>nextObject (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.nextObject)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>project (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.project)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>readBufferedDocuments (number)](#apidoc.element.mongoskin.connect.Cursor.prototype.readBufferedDocuments)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>returnKey (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.returnKey)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>rewind ()](#apidoc.element.mongoskin.connect.Cursor.prototype.rewind)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>setCursorBatchSize (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.setCursorBatchSize)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>setCursorLimit (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.setCursorLimit)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>setCursorOption (field, value)](#apidoc.element.mongoskin.connect.Cursor.prototype.setCursorOption)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>setCursorSkip (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.setCursorSkip)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>setReadPreference (r)](#apidoc.element.mongoskin.connect.Cursor.prototype.setReadPreference)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>showRecordId (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.showRecordId)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>skip (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.skip)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>snapshot (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.snapshot)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>sort (keyOrList, direction)](#apidoc.element.mongoskin.connect.Cursor.prototype.sort)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>stream (options)](#apidoc.element.mongoskin.connect.Cursor.prototype.stream)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>toArray (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.toArray)
1.  object <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>namespace
1.  object <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>readPreference

#### [module mongoskin.connect.Db](#apidoc.module.mongoskin.connect.Db)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>Db (databaseName, topology, options)](#apidoc.element.mongoskin.connect.Db.Db)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.</span>super_ ()](#apidoc.element.mongoskin.connect.Db.super_)
1.  object <span class="apidocSignatureSpan">mongoskin.connect.Db.</span>define
1.  string <span class="apidocSignatureSpan">mongoskin.connect.Db.</span>SYSTEM_COMMAND_COLLECTION
1.  string <span class="apidocSignatureSpan">mongoskin.connect.Db.</span>SYSTEM_INDEX_COLLECTION
1.  string <span class="apidocSignatureSpan">mongoskin.connect.Db.</span>SYSTEM_JS_COLLECTION
1.  string <span class="apidocSignatureSpan">mongoskin.connect.Db.</span>SYSTEM_NAMESPACE_COLLECTION
1.  string <span class="apidocSignatureSpan">mongoskin.connect.Db.</span>SYSTEM_PROFILE_COLLECTION
1.  string <span class="apidocSignatureSpan">mongoskin.connect.Db.</span>SYSTEM_USER_COLLECTION

#### [module mongoskin.connect.Db.prototype](#apidoc.module.mongoskin.connect.Db.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>addChild (db)](#apidoc.element.mongoskin.connect.Db.prototype.addChild)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>addUser (username, password, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.addUser)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>admin ()](#apidoc.element.mongoskin.connect.Db.prototype.admin)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>authenticate (username, password, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.authenticate)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>close (force, callback)](#apidoc.element.mongoskin.connect.Db.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>collection (name, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.collection)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>collections (callback)](#apidoc.element.mongoskin.connect.Db.prototype.collections)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>command (command, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.command)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>createCollection (name, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.createCollection)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>createIndex (name, fieldOrSpec, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.createIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>db (dbName, options)](#apidoc.element.mongoskin.connect.Db.prototype.db)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>dropCollection (name, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.dropCollection)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>dropDatabase (options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.dropDatabase)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>ensureIndex (name, fieldOrSpec, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.ensureIndex)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>eval (code, parameters, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.eval)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>executeDbAdminCommand (selector, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.executeDbAdminCommand)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>indexInformation (name, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.indexInformation)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>listCollections (filter, options)](#apidoc.element.mongoskin.connect.Db.prototype.listCollections)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>logout (options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.logout)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>open (callback)](#apidoc.element.mongoskin.connect.Db.prototype.open)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>removeUser (username, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.removeUser)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>renameCollection (fromCollection, toCollection, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.renameCollection)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>stats (options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.stats)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>unref ()](#apidoc.element.mongoskin.connect.Db.prototype.unref)

#### [module mongoskin.connect.GridStore](#apidoc.module.mongoskin.connect.GridStore)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>GridStore (db, id, filename, mode, options)](#apidoc.element.mongoskin.connect.GridStore.GridStore)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>exist (db, fileIdObject, rootCollection, options, callback)](#apidoc.element.mongoskin.connect.GridStore.exist)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>list (db, rootCollection, options, callback)](#apidoc.element.mongoskin.connect.GridStore.list)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>read (db, name, length, offset, options, callback)](#apidoc.element.mongoskin.connect.GridStore.read)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>readlines (db, name, separator, options, callback)](#apidoc.element.mongoskin.connect.GridStore.readlines)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>unlink (db, names, options, callback)](#apidoc.element.mongoskin.connect.GridStore.unlink)
1.  number <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>IO_SEEK_CUR
1.  number <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>IO_SEEK_END
1.  number <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>IO_SEEK_SET
1.  object <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>define
1.  string <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>DEFAULT_CONTENT_TYPE
1.  string <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>DEFAULT_ROOT_COLLECTION

#### [module mongoskin.connect.GridStore.prototype](#apidoc.module.mongoskin.connect.GridStore.prototype)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>chunkCollection (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.chunkCollection)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>close (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.close)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>collection (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.collection)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>destroy ()](#apidoc.element.mongoskin.connect.GridStore.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>eof ()](#apidoc.element.mongoskin.connect.GridStore.prototype.eof)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>getc (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.getc)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>open (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.open)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>puts (string, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.puts)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>read (length, buffer, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.read)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>readlines (separator, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.readlines)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>rewind (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.rewind)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>seek (position, seekLocation, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.seek)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>stream ()](#apidoc.element.mongoskin.connect.GridStore.prototype.stream)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>tell (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.tell)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>unlink (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.unlink)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>write (data, close, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.write)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>writeFile (file, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.writeFile)

#### [module mongoskin.connect.MongoClient](#apidoc.module.mongoskin.connect.MongoClient)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.</span>MongoClient ()](#apidoc.element.mongoskin.connect.MongoClient.MongoClient)
1.  [function <span class="apidocSignatureSpan">mongoskin.connect.MongoClient.</span>connect (url, options, callback)](#apidoc.element.mongoskin.connect.MongoClient.connect)
1.  object <span class="apidocSignatureSpan">mongoskin.connect.MongoClient.</span>define

#### [module mongoskin.cursor](#apidoc.module.mongoskin.cursor)
1.  [function <span class="apidocSignatureSpan">mongoskin.cursor.</span>SkinCursor ()](#apidoc.element.mongoskin.cursor.SkinCursor)

#### [module mongoskin.db](#apidoc.module.mongoskin.db)
1.  [function <span class="apidocSignatureSpan">mongoskin.db.</span>SkinDb ()](#apidoc.element.mongoskin.db.SkinDb)

#### [module mongoskin.grid_store](#apidoc.module.mongoskin.grid_store)
1.  [function <span class="apidocSignatureSpan">mongoskin.grid_store.</span>SkinGridStore ()](#apidoc.element.mongoskin.grid_store.SkinGridStore)

#### [module mongoskin.helper](#apidoc.module.mongoskin.helper)
1.  [function <span class="apidocSignatureSpan">mongoskin.helper.</span>isObjectID (idstr)](#apidoc.element.mongoskin.helper.isObjectID)
1.  [function <span class="apidocSignatureSpan">mongoskin.helper.</span>toObjectID (hex)](#apidoc.element.mongoskin.helper.toObjectID)

#### [module mongoskin.mongo_client](#apidoc.module.mongoskin.mongo_client)
1.  [function <span class="apidocSignatureSpan">mongoskin.mongo_client.</span>SkinMongoClient ()](#apidoc.element.mongoskin.mongo_client.SkinMongoClient)

#### [module mongoskin.utils](#apidoc.module.mongoskin.utils)
1.  [function <span class="apidocSignatureSpan">mongoskin.utils.</span>makeSkinClass (NativeClass, useNativeConstructor)](#apidoc.element.mongoskin.utils.makeSkinClass)



# <a name="apidoc.module.mongoskin"></a>[module mongoskin](#apidoc.module.mongoskin)

#### <a name="apidoc.element.mongoskin.Admin"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Admin ()](#apidoc.element.mongoskin.Admin)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.BSONRegExp"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>BSONRegExp (pattern, options)](#apidoc.element.mongoskin.BSONRegExp)
- description and source-code
```javascript
function BSONRegExp(pattern, options) {
  if(!(this instanceof BSONRegExp)) return new BSONRegExp();

  // Execute
  this._bsontype = 'BSONRegExp';
  this.pattern = pattern || '';
  this.options = options || '';

  // Validate options
  for(var i = 0; i < this.options.length; i++) {
    if(!(this.options[i] == 'i'
      || this.options[i] == 'm'
      || this.options[i] == 'x'
      || this.options[i] == 'l'
      || this.options[i] == 's'
      || this.options[i] == 'u'
    )) {
      throw new Error('the regular expression options [' + this.options[i] + "] is not supported");
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Binary"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Binary (buffer, subType)](#apidoc.element.mongoskin.Binary)
- description and source-code
```javascript
function Binary(buffer, subType) {
  if(!(this instanceof Binary)) return new Binary(buffer, subType);

  this._bsontype = 'Binary';

  if(buffer instanceof Number) {
    this.sub_type = buffer;
    this.position = 0;
  } else {
    this.sub_type = subType == null ? BSON_BINARY_SUBTYPE_DEFAULT : subType;
    this.position = 0;
  }

  if(buffer != null && !(buffer instanceof Number)) {
    // Only accept Buffer, Uint8Array or Arrays
    if(typeof buffer == 'string') {
      // Different ways of writing the length of the string for the different types
      if(typeof Buffer != 'undefined') {
        this.buffer = new Buffer(buffer);
      } else if(typeof Uint8Array != 'undefined' || (Object.prototype.toString.call(buffer) == '[object Array]')) {
        this.buffer = writeStringToArray(buffer);
      } else {
        throw new Error("only String, Buffer, Uint8Array or Array accepted");
      }
    } else {
      this.buffer = buffer;
    }
    this.position = buffer.length;
  } else {
    if(typeof Buffer != 'undefined') {
      this.buffer =  new Buffer(Binary.BUFFER_SIZE);
    } else if(typeof Uint8Array != 'undefined'){
      this.buffer = new Uint8Array(new ArrayBuffer(Binary.BUFFER_SIZE));
    } else {
      this.buffer = new Array(Binary.BUFFER_SIZE);
    }
    // Set position to start of buffer
    this.position = 0;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Chunk"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Chunk (file, mongoObject, writeConcern)](#apidoc.element.mongoskin.Chunk)
- description and source-code
```javascript
Chunk = function (file, mongoObject, writeConcern) {
  if(!(this instanceof Chunk)) return new Chunk(file, mongoObject);

  this.file = file;
  var mongoObjectFinal = mongoObject == null ? {} : mongoObject;
  this.writeConcern = writeConcern || {w:1};
  this.objectId = mongoObjectFinal._id == null ? new ObjectID() : mongoObjectFinal._id;
  this.chunkNumber = mongoObjectFinal.n == null ? 0 : mongoObjectFinal.n;
  this.data = new Binary();

  if(typeof mongoObjectFinal.data == "string") {
    var buffer = new Buffer(mongoObjectFinal.data.length);
    buffer.write(mongoObjectFinal.data, 0, mongoObjectFinal.data.length, 'binary');
    this.data = new Binary(buffer);
  } else if(Array.isArray(mongoObjectFinal.data)) {
    buffer = new Buffer(mongoObjectFinal.data.length);
    var data = mongoObjectFinal.data.join('');
    buffer.write(data, 0, data.length, 'binary');
    this.data = new Binary(buffer);
  } else if(mongoObjectFinal.data && mongoObjectFinal.data._bsontype === 'Binary') {
    this.data = mongoObjectFinal.data;
  } else if(!Buffer.isBuffer(mongoObjectFinal.data) && !(mongoObjectFinal.data == null)){
    throw Error("Illegal chunk format");
  }

  // Update position
  this.internalPosition = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Code"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Code (code, scope)](#apidoc.element.mongoskin.Code)
- description and source-code
```javascript
function Code(code, scope) {
  if(!(this instanceof Code)) return new Code(code, scope);
  this._bsontype = 'Code';
  this.code = code;
  this.scope = scope;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Collection ()](#apidoc.element.mongoskin.Collection)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>CoreConnection (messageHandler, options)](#apidoc.element.mongoskin.CoreConnection)
- description and source-code
```javascript
CoreConnection = function (messageHandler, options) {
  // Add event listener
  EventEmitter.call(this);
  // Set empty if no options passed
  this.options = options || {};
  // Identification information
  this.id = _id++;
  // Logger instance
  this.logger = Logger('Connection', options);
  // No bson parser passed in
  if(!options.bson) throw new Error("must pass in valid bson parser");
  // Get bson parser
  this.bson = options.bson;
  // Grouping tag used for debugging purposes
  this.tag = options.tag;
  // Message handler
  this.messageHandler = messageHandler;

  // Max BSON message size
  this.maxBsonMessageSize = options.maxBsonMessageSize || (1024 * 1024 * 16 * 4);
  // Debug information
  if(this.logger.isDebug()) this.logger.debug(f('creating connection %s with options [%s]', this.id, JSON.stringify(debugOptions
(debugFields, options))));

  // Default options
  this.port = options.port || 27017;
  this.host = options.host || 'localhost';
  this.keepAlive = typeof options.keepAlive == 'boolean' ? options.keepAlive : true;
  this.keepAliveInitialDelay = options.keepAliveInitialDelay || 0;
  this.noDelay = typeof options.noDelay == 'boolean' ? options.noDelay : true;
  this.connectionTimeout = options.connectionTimeout || 0;
  this.socketTimeout = options.socketTimeout || 0;

  // If connection was destroyed
  this.destroyed = false;

  // Check if we have a domain socket
  this.domainSocket = this.host.indexOf('\/') != -1;

  // Serialize commands using function
  this.singleBufferSerializtion = typeof options.singleBufferSerializtion == 'boolean' ? options.singleBufferSerializtion : true
;
  this.serializationFunction = this.singleBufferSerializtion ? 'toBinUnified' : 'toBin';

  // SSL options
  this.ca = options.ca || null;
  this.crl = options.crl || null;
  this.cert = options.cert || null;
  this.key = options.key || null;
  this.passphrase = options.passphrase || null;
  this.ssl = typeof options.ssl == 'boolean' ? options.ssl : false;
  this.rejectUnauthorized = typeof options.rejectUnauthorized == 'boolean' ? options.rejectUnauthorized : true;
  this.checkServerIdentity = typeof options.checkServerIdentity == 'boolean'
    || typeof options.checkServerIdentity == 'function' ? options.checkServerIdentity : true;

  // If ssl not enabled
  if(!this.ssl) this.rejectUnauthorized = false;

  // Response options
  this.responseOptions = {
    promoteLongs: typeof options.promoteLongs == 'boolean' ?  options.promoteLongs : true,
    promoteValues: typeof options.promoteValues == 'boolean' ? options.promoteValues : true,
    promoteBuffers: typeof options.promoteBuffers == 'boolean' ? options.promoteBuffers: false
  }

  // Flushing
  this.flushing = false;
  this.queue = [];

  // Internal state
  this.connection = null;
  this.writeStream = null;

  // Create hash method
  var hash = crypto.createHash('sha1');
  hash.update(f('%s:%s', this.host, this.port));

  // Create a hash name
  this.hashedName = hash.digest('hex');

  // All operations in flight on the connection
  this.workItems = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>CoreServer (options)](#apidoc.element.mongoskin.CoreServer)
- description and source-code
```javascript
CoreServer = function (options) {
  options = options || {};

  // Add event listener
  EventEmitter.call(this);

  // Server instance id
  this.id = id++;

  // Internal state
  this.s = {
    // Options
    options: options,
    // Logger
    logger: Logger('Server', options),
    // Factory overrides
    Cursor: options.cursorFactory || BasicCursor,
    // BSON instance
    bson: options.bson || new BSON([BSON.Binary, BSON.Code, BSON.DBRef, BSON.Decimal128,
      BSON.Double, BSON.Int32, BSON.Long, BSON.Map, BSON.MaxKey, BSON.MinKey,
      BSON.ObjectId, BSON.BSONRegExp, BSON.Symbol, BSON.Timestamp]),
    // Pool
    pool: null,
    // Disconnect handler
    disconnectHandler: options.disconnectHandler,
    // Monitor thread (keeps the connection alive)
    monitoring: typeof options.monitoring == 'boolean' ? options.monitoring : true,
    // Is the server in a topology
    inTopology: typeof options.inTopology == 'boolean' ? options.inTopology : false,
    // Monitoring timeout
    monitoringInterval: typeof options.monitoringInterval == 'number'
      ? options.monitoringInterval
      : 5000,
    // Topology id
    topologyId: -1
  }

  // Curent ismaster
  this.ismaster = null;
  // Current ping time
  this.lastIsMasterMS = -1;
  // The monitoringProcessId
  this.monitoringProcessId = null;
  // Initial connection
  this.initalConnect = true;
  // Wire protocol handler, default to oldest known protocol handler
  // this gets changed when the first ismaster is called.
  this.wireProtocolHandler = new PreTwoSixWireProtocolSupport();
  // Default type
  this._type = 'server';
  // Set the client info
  this.clientInfo = createClientInfo(options);

  // Max Stalleness values
  // last time we updated the ismaster state
  this.lastUpdateTime = 0;
  // Last write time
  this.lastWriteDate = 0;
  // Stalleness
  this.staleness = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Cursor ()](#apidoc.element.mongoskin.Cursor)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.DBRef"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>DBRef (namespace, oid, db)](#apidoc.element.mongoskin.DBRef)
- description and source-code
```javascript
function DBRef(namespace, oid, db) {
  if(!(this instanceof DBRef)) return new DBRef(namespace, oid, db);

  this._bsontype = 'DBRef';
  this.namespace = namespace;
  this.oid = oid;
  this.db = db;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Db ()](#apidoc.element.mongoskin.Db)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Decimal128"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Decimal128 (bytes)](#apidoc.element.mongoskin.Decimal128)
- description and source-code
```javascript
Decimal128 = function (bytes) {
  this._bsontype = 'Decimal128';
  this.bytes = bytes;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Double"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Double (value)](#apidoc.element.mongoskin.Double)
- description and source-code
```javascript
function Double(value) {
  if(!(this instanceof Double)) return new Double(value);

  this._bsontype = 'Double';
  this.value = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridFSBucket"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>GridFSBucket (db, options)](#apidoc.element.mongoskin.GridFSBucket)
- description and source-code
```javascript
function GridFSBucket(db, options) {
  Emitter.apply(this);
  this.setMaxListeners(0);

  if (options && typeof options === 'object') {
    options = shallowClone(options);
    var keys = Object.keys(DEFAULT_GRIDFS_BUCKET_OPTIONS);
    for (var i = 0; i < keys.length; ++i) {
      if (!options[keys[i]]) {
        options[keys[i]] = DEFAULT_GRIDFS_BUCKET_OPTIONS[keys[i]];
      }
    }
  } else {
    options = DEFAULT_GRIDFS_BUCKET_OPTIONS;
  }

  this.s = {
    db: db,
    options: options,
    _chunksCollection: db.collection(options.bucketName + '.chunks'),
    _filesCollection: db.collection(options.bucketName + '.files'),
    checkedIndexes: false,
    calledOpenUploadStream: false,
    promiseLibrary: db.s.promiseLibrary ||
      (typeof global.Promise == 'function' ? global.Promise : require('es6-promise').Promise)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>GridStore ()](#apidoc.element.mongoskin.GridStore)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Int32"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Int32 (value)](#apidoc.element.mongoskin.Int32)
- description and source-code
```javascript
Int32 = function (value) {
  if(!(this instanceof Int32)) return new Int32(value);

  this._bsontype = 'Int32';
  this.value = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Logger (className, options)](#apidoc.element.mongoskin.Logger)
- description and source-code
```javascript
Logger = function (className, options) {
  if(!(this instanceof Logger)) return new Logger(className, options);
  options = options || {};

  // Current reference
  this.className = className;

  // Current logger
  if(options.logger) {
    currentLogger = options.logger;
  } else if(currentLogger == null) {
    currentLogger = console.log;
  }

  // Set level of logging, default is error
  if(options.loggerLevel) {
    level = options.loggerLevel || 'error';
  }

  // Add all class names
  if(filteredClasses[this.className] == null) classFilters[this.className] =  true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Long (low, high)](#apidoc.element.mongoskin.Long)
- description and source-code
```javascript
function Long(low, high) {
  if(!(this instanceof Long)) return new Long(low, high);

  this._bsontype = 'Long';
<span class="apidocCodeCommentSpan">  /**
   * @type {number}
   * @ignore
   */
</span>  this.low_ = low | 0;  // force into 32 signed bits.

  /**
   * @type {number}
   * @ignore
   */
  this.high_ = high | 0;  // force into 32 signed bits.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Map"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Map ()](#apidoc.element.mongoskin.Map)
- description and source-code
```javascript
function Map() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.MaxKey"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>MaxKey ()](#apidoc.element.mongoskin.MaxKey)
- description and source-code
```javascript
function MaxKey() {
  if(!(this instanceof MaxKey)) return new MaxKey();

  this._bsontype = 'MaxKey';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.MinKey"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>MinKey ()](#apidoc.element.mongoskin.MinKey)
- description and source-code
```javascript
function MinKey() {
  if(!(this instanceof MinKey)) return new MinKey();

  this._bsontype = 'MinKey';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.MongoClient"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>MongoClient ()](#apidoc.element.mongoskin.MongoClient)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.MongoError"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>MongoError (message)](#apidoc.element.mongoskin.MongoError)
- description and source-code
```javascript
function MongoError(message) {
  this.name = 'MongoError';
  this.message = message;
  Error.captureStackTrace(this, MongoError);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Mongos (servers, options)](#apidoc.element.mongoskin.Mongos)
- description and source-code
```javascript
Mongos = function (servers, options) {
  if(!(this instanceof Mongos)) return new Mongos(servers, options);
  options = options || {};
  var self = this;

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Ensure all the instances are Server
  for(var i = 0; i < servers.length; i++) {
    if(!(servers[i] instanceof Server)) {
      throw MongoError.create({message: "all seed list instances must be of the Server type", driver:true});
    }
  }

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Set up event emitter
  EventEmitter.call(this);

  // Build seed list
  var seedlist = servers.map(function(x) {
    return {host: x.host, port: x.port}
  });

  // Get the reconnect option
  var reconnect = typeof options.auto_reconnect == 'boolean' ? options.auto_reconnect : true;
  reconnect = typeof options.autoReconnect == 'boolean' ? options.autoReconnect : reconnect;

  // Clone options
  var clonedOptions = mergeOptions({}, {
    disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: reconnect,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Build default client information
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create the Mongos
  var mongos = new CMongos(seedlist, clonedOptions)
  // Server capabilities
  var sCapabilities = null;

  // Internal state
  this.s = {
    // Create the Mongos
      mongos: mongos
    // Server capabilities
    , sCapabilities: sCapabilities
    // Debug turned on
    , debug: clonedOptions.debug
    // Store option defaults
    , storeOptions: storeOptions
    // Cloned options
    , clonedOptions: clonedOptions
    // Actual store of callbacks
    , store: store
    // Options
    , options: options
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>ObjectID (id)](#apidoc.element.mongoskin.ObjectID)
- description and source-code
```javascript
function ObjectID(id) {
  // Duck-typing to support ObjectId from different npm packages
  if(id instanceof ObjectID) return id;
  if(!(this instanceof ObjectID)) return new ObjectID(id);

  this._bsontype = 'ObjectID';

  // The most common usecase (blank id, new objectId instance)
  if(id == null || typeof id == 'number') {
    // Generate a new id
    this.id = this.generate(id);
    // If we are caching the hex string
    if(ObjectID.cacheHexString) this.__id = this.toString('hex');
    // Return the object
    return;
  }

  // Check if the passed in id is valid
  var valid = ObjectID.isValid(id);

  // Throw an error if it's not a valid setup
  if(!valid && id != null){
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  } else if(valid && typeof id == 'string' && id.length == 24 && hasBufferType) {
    return new ObjectID(new Buffer(id, 'hex'));
  } else if(valid && typeof id == 'string' && id.length == 24) {
    return ObjectID.createFromHexString(id);
  } else if(id != null && id.length === 12) {
    // assume 12 byte string
    this.id = id;
  } else if(id != null && id.toHexString) {
    // Duck-typing to support ObjectId from different npm packages
    return id;
  } else {
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  }

  if(ObjectID.cacheHexString) this.__id = this.toString('hex');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectId"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>ObjectId (id)](#apidoc.element.mongoskin.ObjectId)
- description and source-code
```javascript
function ObjectID(id) {
  // Duck-typing to support ObjectId from different npm packages
  if(id instanceof ObjectID) return id;
  if(!(this instanceof ObjectID)) return new ObjectID(id);

  this._bsontype = 'ObjectID';

  // The most common usecase (blank id, new objectId instance)
  if(id == null || typeof id == 'number') {
    // Generate a new id
    this.id = this.generate(id);
    // If we are caching the hex string
    if(ObjectID.cacheHexString) this.__id = this.toString('hex');
    // Return the object
    return;
  }

  // Check if the passed in id is valid
  var valid = ObjectID.isValid(id);

  // Throw an error if it's not a valid setup
  if(!valid && id != null){
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  } else if(valid && typeof id == 'string' && id.length == 24 && hasBufferType) {
    return new ObjectID(new Buffer(id, 'hex'));
  } else if(valid && typeof id == 'string' && id.length == 24) {
    return ObjectID.createFromHexString(id);
  } else if(id != null && id.length === 12) {
    // assume 12 byte string
    this.id = id;
  } else if(id != null && id.toHexString) {
    // Duck-typing to support ObjectId from different npm packages
    return id;
  } else {
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  }

  if(ObjectID.cacheHexString) this.__id = this.toString('hex');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReadPreference"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>ReadPreference (mode, tags, options)](#apidoc.element.mongoskin.ReadPreference)
- description and source-code
```javascript
ReadPreference = function (mode, tags, options) {
  if(!(this instanceof ReadPreference)) {
    return new ReadPreference(mode, tags, options);
  }

  this._type = 'ReadPreference';
  this.mode = mode;
  this.tags = tags;
  this.options =  options;

  // If no tags were passed in
  if(tags && typeof tags == 'object' && !Array.isArray(tags)) {
    if(tags.maxStalenessSeconds) {
      this.options = tags;
      this.tags = null;
    }
  }

  // Add the maxStalenessSeconds value to the read Preference
  if(this.options && this.options.maxStalenessSeconds) {
    this.maxStalenessSeconds = this.options.maxStalenessSeconds;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>ReplSet (servers, options)](#apidoc.element.mongoskin.ReplSet)
- description and source-code
```javascript
ReplSet = function (servers, options) {
  if(!(this instanceof ReplSet)) return new ReplSet(servers, options);
  options = options || {};
  var self = this;
  // Set up event emitter
  EventEmitter.call(this);

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Ensure all the instances are Server
  for(var i = 0; i < servers.length; i++) {
    if(!(servers[i] instanceof Server)) {
      throw MongoError.create({message: "all seed list instances must be of the Server type", driver:true});
    }
  }

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Build seed list
  var seedlist = servers.map(function(x) {
    return {host: x.host, port: x.port}
  });

  // Clone options
  var clonedOptions = mergeOptions({}, {
    disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: false,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Client info
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create the ReplSet
  var replset = new CReplSet(seedlist, clonedOptions);

  // Listen to reconnect event
  replset.on('reconnect', function() {
    self.emit('reconnect');
    store.execute();
  });

  // Internal state
  this.s = {
    // Replicaset
    replset: replset
    // Server capabilities
    , sCapabilities: null
    // Debug tag
    , tag: options.tag
    // Store options
    , storeOptions: storeOptions
    // Cloned options
    , clonedOptions: clonedOptions
    // Store
    , store: store
    // Options
    , options: options
  }

  // Debug
  if(clonedOptions.debug) {
    // Last ismaster
    Object.defineProperty(this, 'replset', {
      enumerable:true, get: function() { return replset; }
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Server (host, port, options)](#apidoc.element.mongoskin.Server)
- description and source-code
```javascript
Server = function (host, port, options) {
  options = options || {};
  if(!(this instanceof Server)) return new Server(host, port, options);
  EventEmitter.call(this);
  var self = this;

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Detect if we have a socket connection
  if(host.indexOf('\/') != -1) {
    if(port != null && typeof port == 'object') {
      options = port;
      port = null;
    }
  } else if(port == null) {
    throw MongoError.create({message: 'port must be specified', driver:true});
  }

  // Get the reconnect option
  var reconnect = typeof options.auto_reconnect == 'boolean' ? options.auto_reconnect : true;
  reconnect = typeof options.autoReconnect == 'boolean' ? options.autoReconnect : reconnect;

  // Clone options
  var clonedOptions = mergeOptions({}, {
    host: host, port: port, disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: reconnect,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Build default client information
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create an instance of a server instance from mongodb-core
  var server = new CServer(clonedOptions);

  // Define the internal properties
  this.s = {
    // Create an instance of a server instance from mongodb-core
      server: server
    // Server capabilities
    , sCapabilities: null
    // Cloned options
    , clonedOptions: clonedOptions
    // Reconnect
    , reconnect: clonedOptions.reconnect
    // Emit error
    , emitError: clonedOptions.emitError
    // Pool size
    , poolSize: clonedOptions.size
    // Store Options
    , storeOptions: storeOptions
    // Store
    , store: store
    // Host
    , host: host
    // Port
    , port: port
    // Options
    , options: options
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Symbol"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Symbol (value)](#apidoc.element.mongoskin.Symbol)
- description and source-code
```javascript
function Symbol(value) {
  if(!(this instanceof Symbol)) return new Symbol(value);
  this._bsontype = 'Symbol';
  this.value = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Timestamp (low, high)](#apidoc.element.mongoskin.Timestamp)
- description and source-code
```javascript
function Timestamp(low, high) {
  if(!(this instanceof Timestamp)) return new Timestamp(low, high);
  this._bsontype = 'Timestamp';
<span class="apidocCodeCommentSpan">  /**
   * @type {number}
   * @ignore
   */
</span>  this.low_ = low | 0;  // force into 32 signed bits.

  /**
   * @type {number}
   * @ignore
   */
  this.high_ = high | 0;  // force into 32 signed bits.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>connect (url, options, callback)](#apidoc.element.mongoskin.connect)
- description and source-code
```javascript
connect = function (url, options, callback) {
  var args = Array.prototype.slice.call(arguments, 1);
  callback = typeof args[args.length - 1] == 'function' ? args.pop() : null;
  options = args.length ? args.shift() : null;
  options = options || {};

  // Validate options object
  var err = validOptions(options);

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Return a promise
  if(typeof callback != 'function') {
    return new promiseLibrary(function(resolve, reject) {
      // Did we have a validation error
      if(err) return reject(err);
      // Attempt to connect
      connect(url, options, function(err, db) {
        if(err) return reject(err);
        resolve(db);
      });
    });
  }

  // Did we have a validation error
  if(err) return callback(err);
  // Fallback to callback based connect
  connect(url, options, callback);
}
```
- example usage
```shell
...
var Db = mongo.Db;
var Server = mongo.Server;
var MongoClient = mongo.MongoClient;
var ReplSetServers = mongo.ReplSetServers;
...
'''

### MongoClient.connect(...)

returns a 'Db' instance

alias origin 'MongoClient.connect(..., function(err, db) { .... })'

origin:
...
```

#### <a name="apidoc.element.mongoskin.connect.Admin"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>connect.Admin (db, topology, promiseLibrary)](#apidoc.element.mongoskin.connect.Admin)
- description and source-code
```javascript
connect.Admin = function (db, topology, promiseLibrary) {
  if(!(this instanceof Admin)) return new Admin(db, topology);

  // Internal state
  this.s = {
      db: db
    , topology: topology
    , promiseLibrary: promiseLibrary
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>connect.Collection (db, topology, dbName, name, pkFactory, options)](#apidoc.element.mongoskin.connect.Collection)
- description and source-code
```javascript
connect.Collection = function (db, topology, dbName, name, pkFactory, options) {
  checkCollectionName(name);

  // Unpack variables
  var internalHint = null;
  var slaveOk = options == null || options.slaveOk == null ? db.slaveOk : options.slaveOk;
  var serializeFunctions = options == null || options.serializeFunctions == null ? db.s.options.serializeFunctions : options.serializeFunctions
;
  var raw = options == null || options.raw == null ? db.s.options.raw : options.raw;
  var promoteLongs = options == null || options.promoteLongs == null ? db.s.options.promoteLongs : options.promoteLongs;
  var promoteValues = options == null || options.promoteValues == null ? db.s.options.promoteValues : options.promoteValues;
  var promoteBuffers = options == null || options.promoteBuffers == null ? db.s.options.promoteBuffers : options.promoteBuffers;
  var readPreference = null;
  var collectionHint = null;
  var namespace = f("%s.%s", dbName, name);

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Assign the right collection level readPreference
  if(options && options.readPreference) {
    readPreference = options.readPreference;
  } else if(db.options.readPreference) {
    readPreference = db.options.readPreference;
  }

  // Set custom primary key factory if provided
  pkFactory = pkFactory == null
    ? ObjectID
    : pkFactory;

  // Internal state
  this.s = {
    // Set custom primary key factory if provided
      pkFactory: pkFactory
    // Db
    , db: db
    // Topology
    , topology: topology
    // dbName
    , dbName: dbName
    // Options
    , options: options
    // Namespace
    , namespace: namespace
    // Read preference
    , readPreference: readPreference
    // SlaveOK
    , slaveOk: slaveOk
    // Serialize functions
    , serializeFunctions: serializeFunctions
    // Raw
    , raw: raw
    // promoteLongs
    , promoteLongs: promoteLongs
    // promoteValues
    , promoteValues: promoteValues
    // promoteBuffers
    , promoteBuffers: promoteBuffers
    // internalHint
    , internalHint: internalHint
    // collectionHint
    , collectionHint: collectionHint
    // Name
    , name: name
    // Promise library
    , promiseLibrary: promiseLibrary
    // Read Concern
    , readConcern: options.readConcern
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>connect.Cursor (bson, ns, cmd, options, topology, topologyOptions)](#apidoc.element.mongoskin.connect.Cursor)
- description and source-code
```javascript
connect.Cursor = function (bson, ns, cmd, options, topology, topologyOptions) {
  CoreCursor.apply(this, Array.prototype.slice.call(arguments, 0));
  var self = this;
  var state = Cursor.INIT;
  var streamOptions = {};

  // Tailable cursor options
  var numberOfRetries = options.numberOfRetries || 5;
  var tailableRetryInterval = options.tailableRetryInterval || 500;
  var currentNumberOfRetries = numberOfRetries;

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Set up
  Readable.call(this, {objectMode: true});

  // Internal cursor state
  this.s = {
    // Tailable cursor options
      numberOfRetries: numberOfRetries
    , tailableRetryInterval: tailableRetryInterval
    , currentNumberOfRetries: currentNumberOfRetries
    // State
    , state: state
    // Stream options
    , streamOptions: streamOptions
    // BSON
    , bson: bson
    // Namespace
    , ns: ns
    // Command
    , cmd: cmd
    // Options
    , options: options
    // Topology
    , topology: topology
    // Topology options
    , topologyOptions: topologyOptions
    // Promise library
    , promiseLibrary: promiseLibrary
    // Current doc
    , currentDoc: null
  }

  // Translate correctly
  if(self.s.options.noCursorTimeout == true) {
    self.addCursorFlag('noCursorTimeout', true);
  }

  // Set the sort value
  this.sortValue = self.s.cmd.sort;

  // Get the batchSize
  var batchSize = cmd.cursor && cmd.cursor.batchSize
    ? cmd.cursor && cmd.cursor.batchSize
    : (options.cursor && options.cursor.batchSize ? options.cursor.batchSize : 1000);

  // Set the batchSize
  this.setCursorBatchSize(batchSize);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>connect.Db (databaseName, topology, options)](#apidoc.element.mongoskin.connect.Db)
- description and source-code
```javascript
connect.Db = function (databaseName, topology, options) {
  options = options || {};
  if(!(this instanceof Db)) return new Db(databaseName, topology, options);
  EventEmitter.call(this);
  var self = this;

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Ensure we put the promiseLib in the options
  options.promiseLibrary = promiseLibrary;

  // var self = this;  // Internal state of the db object
  this.s = {
    // Database name
      databaseName: databaseName
    // DbCache
    , dbCache: {}
    // Children db's
    , children: []
    // Topology
    , topology: topology
    // Options
    , options: options
    // Logger instance
    , logger: Logger('Db', options)
    // Get the bson parser
    , bson: topology ? topology.bson : null
    // Authsource if any
    , authSource: options.authSource
    // Unpack read preference
    , readPreference: options.readPreference
    // Set buffermaxEntries
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : -1
    // Parent db (if chained)
    , parentDb: options.parentDb || null
    // Set up the primary key factory or fallback to ObjectID
    , pkFactory: options.pkFactory || ObjectID
    // Get native parser
    , nativeParser: options.nativeParser || options.native_parser
    // Promise library
    , promiseLibrary: promiseLibrary
    // No listener
    , noListener: typeof options.noListener == 'boolean' ? options.noListener : false
    // ReadConcern
    , readConcern: options.readConcern
  }

  // Ensure we have a valid db name
  validateDatabaseName(self.s.databaseName);

  // Add a read Only property
  getSingleProperty(this, 'serverConfig', self.s.topology);
  getSingleProperty(this, 'bufferMaxEntries', self.s.bufferMaxEntries);
  getSingleProperty(this, 'databaseName', self.s.databaseName);

  // This is a child db, do not register any listeners
  if(options.parentDb) return;
  if(this.s.noListener) return;

  // Add listeners
  topology.on('error', createListener(self, 'error', self));
  topology.on('timeout', createListener(self, 'timeout', self));
  topology.on('close', createListener(self, 'close', self));
  topology.on('parseError', createListener(self, 'parseError', self));
  topology.once('open', createListener(self, 'open', self));
  topology.once('fullsetup', createListener(self, 'fullsetup', self));
  topology.once('all', createListener(self, 'all', self));
  topology.on('reconnect', createListener(self, 'reconnect', self));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>connect.GridStore (db, id, filename, mode, options)](#apidoc.element.mongoskin.connect.GridStore)
- description and source-code
```javascript
function GridStore(db, id, filename, mode, options) {
  if(!(this instanceof GridStore)) return new GridStore(db, id, filename, mode, options);
  this.db = db;

  // Handle options
  if(typeof options === 'undefined') options = {};
  // Handle mode
  if(typeof mode === 'undefined') {
    mode = filename;
    filename = undefined;
  } else if(typeof mode == 'object') {
    options = mode;
    mode = filename;
    filename = undefined;
  }

  if(id && id._bsontype == 'ObjectID') {
    this.referenceBy = REFERENCE_BY_ID;
    this.fileId = id;
    this.filename = filename;
  } else if(typeof filename == 'undefined') {
    this.referenceBy = REFERENCE_BY_FILENAME;
    this.filename = id;
    if (mode.indexOf('w') != null) {
      this.fileId = new ObjectID();
    }
  } else {
    this.referenceBy = REFERENCE_BY_ID;
    this.fileId = id;
    this.filename = filename;
  }

  // Set up the rest
  this.mode = mode == null ? "r" : mode;
  this.options = options || {};

  // Opened
  this.isOpen = false;

  // Set the root if overridden
  this.root = this.options['root'] == null ? GridStore.DEFAULT_ROOT_COLLECTION : this.options['root'];
  this.position = 0;
  this.readPreference = this.options.readPreference || db.options.readPreference || ReadPreference.PRIMARY;
  this.writeConcern = _getWriteConcern(db, this.options);
  // Set default chunk size
  this.internalChunkSize = this.options['chunkSize'] == null ? Chunk.DEFAULT_CHUNK_SIZE : this.options['chunkSize'];

  // Get the promiseLibrary
  var promiseLibrary = this.options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Set the promiseLibrary
  this.promiseLibrary = promiseLibrary;

  Object.defineProperty(this, "chunkSize", { enumerable: true
   , get: function () {
       return this.internalChunkSize;
     }
   , set: function(value) {
       if(!(this.mode[0] == "w" && this.position == 0 && this.uploadDate == null)) {
         this.internalChunkSize = this.internalChunkSize;
       } else {
         this.internalChunkSize = value;
       }
     }
  });

  Object.defineProperty(this, "md5", { enumerable: true
   , get: function () {
       return this.internalMd5;
     }
  });

  Object.defineProperty(this, "chunkNumber", { enumerable: true
   , get: function () {
       return this.currentChunk && this.currentChunk.chunkNumber ? this.currentChunk.chunkNumber : null;
     }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.MongoClient"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>connect.MongoClient ()](#apidoc.element.mongoskin.connect.MongoClient)
- description and source-code
```javascript
function MongoClient() {
<span class="apidocCodeCommentSpan">  /**
   * The callback format for results
   * @callback MongoClient~connectCallback
   * @param {MongoError} error An error instance representing the error during the execution.
   * @param {Db} db The connected database.
   */
</span>
  /**
   * Connect to MongoDB using a url as documented at
   *
   *  docs.mongodb.org/manual/reference/connection-string/
   *
   * Note that for replicasets the replicaSet query parameter is required in the 2.0 driver
   *
   * @method
   * @param {string} url The connection URI string
   * @param {object} [options] Optional settings.
   * @param {number} [options.poolSize=5] poolSize The maximum size of the individual server pool.
   * @param {boolean} [options.ssl=false] Enable SSL connection.
   * @param {Buffer} [options.sslCA=undefined] SSL Certificate store binary buffer
   * @param {Buffer} [options.sslCRL=undefined] SSL Certificate revocation list binary buffer
   * @param {Buffer} [options.sslCert=undefined] SSL Certificate binary buffer
   * @param {Buffer} [options.sslKey=undefined] SSL Key file binary buffer
   * @param {string} [options.sslPass=undefined] SSL Certificate pass phrase
   * @param {boolean|function} [options.checkServerIdentity=true] Ensure we check server identify during SSL, set to false to disable
 checking. Only works for Node 0.12.x or higher. You can pass in a boolean or your own checkServerIdentity override function.
   * @param {boolean} [options.autoReconnect=true] Enable autoReconnect for single server instances
   * @param {boolean} [options.noDelay=true] TCP Connection no delay
   * @param {boolean} [options.keepAlive=0] The number of milliseconds to wait before initiating keepAlive on the TCP socket.
   * @param {number} [options.connectTimeoutMS=30000] TCP Connection timeout setting
   * @param {number} [options.socketTimeoutMS=30000] TCP Socket timeout setting
   * @param {number} [options.reconnectTries=30] Server attempt to reconnect #times
   * @param {number} [options.reconnectInterval=1000] Server will wait # milliseconds between retries
   * @param {boolean} [options.ha=true] Control if high availability monitoring runs for Replicaset or Mongos proxies.
   * @param {number} [options.haInterval=10000] The High availability period for replicaset inquiry
   * @param {string} [options.replicaSet=undefined] The Replicaset set name
   * @param {number} [options.secondaryAcceptableLatencyMS=15] Cutoff latency point in MS for Replicaset member selection
   * @param {number} [options.acceptableLatencyMS=15] Cutoff latency point in MS for Mongos proxies selection.
   * @param {boolean} [options.connectWithNoPrimary=false] Sets if the driver should connect even if no primary is available
   * @param {string} [options.authSource=undefined] Define the database to authenticate against
   * @param {(number|string)} [options.w=null] The write concern.
   * @param {number} [options.wtimeout=null] The write concern timeout.
   * @param {boolean} [options.j=false] Specify a journal write concern.
   * @param {boolean} [options.forceServerObjectId=false] Force server to assign _id values instead of driver.
   * @param {boolean} [options.serializeFunctions=false] Serialize functions on any object.
   * @param {Boolean} [options.ignoreUndefined=false] Specify if the BSON serializer should ignore undefined fields.
   * @param {boolean} [options.raw=false] Return document results as raw BSON buffers.
   * @param {boolean} [options.promoteLongs=true] Promotes Long values to number if they fit inside the 53 bits resolution.
   * @param {boolean} [options.promoteBuffers=false] Promotes Binary BSON values to native Node Buffers.
   * @param {boolean} [options.promoteValues=true] Promotes BSON values to native types where possible, set to false to only receive
 wrapper types.
   * @param {number} [options.bufferMaxEntries=-1] Sets a cap on how many operations the driver will buffer up before giving up
on getting a working connection, default is -1 which is unlimited.
   * @param {(ReadPreference|string)} [options.readPreference=null] The preferred ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.db"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>db ()](#apidoc.element.mongoskin.db)
- description and source-code
```javascript
db = function () {
  var args = [].slice.call(arguments);
  var db = new SkinDb();
  db._connect_args = args;
  return db;
}
```
- example usage
```shell
...
Usage
========

Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet
...
```

#### <a name="apidoc.element.mongoskin.instrument"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>instrument (options, callback)](#apidoc.element.mongoskin.instrument)
- description and source-code
```javascript
instrument = function (options, callback) {
  if(typeof options == 'function') callback = options, options = {};
  return new Instrumentation(core, options, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Admin"></a>[module mongoskin.Admin](#apidoc.module.mongoskin.Admin)

#### <a name="apidoc.element.mongoskin.Admin.Admin"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Admin ()](#apidoc.element.mongoskin.Admin.Admin)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin._bindGetter"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.</span>_bindGetter (propName)](#apidoc.element.mongoskin.Admin._bindGetter)
- description and source-code
```javascript
_bindGetter = function (propName) {
    SkinClass.prototype.__defineGetter__(propName, function() {
        return this._native && this._native[propName];// || this['_prop_' + propName];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin._bindMethod"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.</span>_bindMethod (propName)](#apidoc.element.mongoskin.Admin._bindMethod)
- description and source-code
```javascript
_bindMethod = function (propName) {
  SkinClass.prototype[propName] = function() {
    var args = __slice.apply(arguments);
    if (this._state == STATE_OPEN) {
      this._native[propName].apply(this._native, args);
    } else {
      this.open(function(err, p_native) {
          if (err) {
            onError(err, args, skinClassName + '.' + propName);
          } else {
            p_native[propName].apply(p_native, args);
          }
      });
    }
    return this;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin._bindSetter"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.</span>_bindSetter (propName)](#apidoc.element.mongoskin.Admin._bindSetter)
- description and source-code
```javascript
_bindSetter = function (propName) {
    SkinClass.prototype.__defineSetter__(propName, function(value) {
        // this['_prop_' + propName] = value;
        this.open(function(err, p_native) {
            if(err) return onError(err, args, skinClassName + '.' + propName);
            p_native[propName] = value;
        });
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Admin.prototype"></a>[module mongoskin.Admin.prototype](#apidoc.module.mongoskin.Admin.prototype)

#### <a name="apidoc.element.mongoskin.Admin.prototype._close"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>_close (callback)](#apidoc.element.mongoskin.Admin.prototype._close)
- description and source-code
```javascript
_close = function (callback) {
  if(this._native.close) {
    this._native.close(callback)
  } else if(callback) {
    callback();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype._open"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>_open (callback)](#apidoc.element.mongoskin.Admin.prototype._open)
- description and source-code
```javascript
_open = function (callback) {
  var skindb = this._construct_args[0];
  skindb.open(function(err, p_db) {
      if(err) return callback(err);
      callback(null, p_db.admin());
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.addUser"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>addUser ()](#apidoc.element.mongoskin.Admin.prototype.addUser)
- description and source-code
```javascript
addUser = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.authenticate"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>authenticate ()](#apidoc.element.mongoskin.Admin.prototype.authenticate)
- description and source-code
```javascript
authenticate = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.buildInfo"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>buildInfo ()](#apidoc.element.mongoskin.Admin.prototype.buildInfo)
- description and source-code
```javascript
buildInfo = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>close (callback)](#apidoc.element.mongoskin.Admin.prototype.close)
- description and source-code
```javascript
close = function (callback) {
  if (this._state === STATE_CLOSE) {
    callback && callback();
  } else if (this._state === STATE_OPEN) {
    this._state = STATE_CLOSE;
    this._close(callback);
  } else if (this._state === STATE_OPENNING) {
    var self = this;
    this._emitter.once('open', function (err, db) {
        self.close(callback);
    });
  }
  this._native = null;
  return this;
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.command"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>command ()](#apidoc.element.mongoskin.Admin.prototype.command)
- description and source-code
```javascript
command = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.isOpen"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>isOpen ()](#apidoc.element.mongoskin.Admin.prototype.isOpen)
- description and source-code
```javascript
isOpen = function () {
  return this._state === STATE_OPEN;
}
```
- example usage
```shell
...
 * @param {Function(err, docs)} callback
 * @return {SkinCursor|SkinCollection} if last argument is not a function, then returns a SkinCursor,
 *   otherise return this
 * @api public
 */
SkinCollection.prototype.find = function (query, options, callback) {
var args = __slice.call(arguments);
if(this.isOpen()) {
  return this._native.find.apply(this._native, args);
}
if (args.length > 0 && typeof args[args.length - 1] === 'function') {
  this._find.apply(this, args);
  return this;
} else {
  var cursor = new SkinCursor();
...
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.listDatabases"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>listDatabases ()](#apidoc.element.mongoskin.Admin.prototype.listDatabases)
- description and source-code
```javascript
listDatabases = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.logout"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>logout ()](#apidoc.element.mongoskin.Admin.prototype.logout)
- description and source-code
```javascript
logout = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.open"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>open (callback)](#apidoc.element.mongoskin.Admin.prototype.open)
- description and source-code
```javascript
open = function (callback) {
  switch (this._state) {
    case STATE_OPEN:
      callback(null, this._native);
      break;
    case STATE_OPENNING:
      this._emitter.once('open', callback);
      break;
    default:
      this._emitter.once('open', callback);
      this._state = STATE_OPENNING;
      var self = this;
      this._open(function(err, p_native) {
          if (err) {
            self._state = STATE_CLOSE;
          } else {
            self._state = STATE_OPEN;
            self._native = p_native;
          }
          self._emitter.emit('open', err, p_native);
      });
  }
  return this;
}
```
- example usage
```shell
...

alias origin 'db.collection(..., function(err, collection) {....})'

origin:

'''js
var db = new Db(...);
db.open(function(err, db) {
    db.collection('myCollection', {strict: true}, function(err, myCollection) {
        // myCollection.find() ...
    });
});
'''

mongoskin:
...
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.ping"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>ping ()](#apidoc.element.mongoskin.Admin.prototype.ping)
- description and source-code
```javascript
ping = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.profilingInfo"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>profilingInfo ()](#apidoc.element.mongoskin.Admin.prototype.profilingInfo)
- description and source-code
```javascript
profilingInfo = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.profilingLevel"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>profilingLevel ()](#apidoc.element.mongoskin.Admin.prototype.profilingLevel)
- description and source-code
```javascript
profilingLevel = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.removeUser"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>removeUser ()](#apidoc.element.mongoskin.Admin.prototype.removeUser)
- description and source-code
```javascript
removeUser = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.replSetGetStatus"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>replSetGetStatus ()](#apidoc.element.mongoskin.Admin.prototype.replSetGetStatus)
- description and source-code
```javascript
replSetGetStatus = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.serverInfo"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>serverInfo ()](#apidoc.element.mongoskin.Admin.prototype.serverInfo)
- description and source-code
```javascript
serverInfo = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.serverStatus"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>serverStatus ()](#apidoc.element.mongoskin.Admin.prototype.serverStatus)
- description and source-code
```javascript
serverStatus = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.setProfilingLevel"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>setProfilingLevel ()](#apidoc.element.mongoskin.Admin.prototype.setProfilingLevel)
- description and source-code
```javascript
setProfilingLevel = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Admin.prototype.validateCollection"></a>[function <span class="apidocSignatureSpan">mongoskin.Admin.prototype.</span>validateCollection ()](#apidoc.element.mongoskin.Admin.prototype.validateCollection)
- description and source-code
```javascript
validateCollection = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.BSONRegExp"></a>[module mongoskin.BSONRegExp](#apidoc.module.mongoskin.BSONRegExp)

#### <a name="apidoc.element.mongoskin.BSONRegExp.BSONRegExp"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>BSONRegExp (pattern, options)](#apidoc.element.mongoskin.BSONRegExp.BSONRegExp)
- description and source-code
```javascript
function BSONRegExp(pattern, options) {
  if(!(this instanceof BSONRegExp)) return new BSONRegExp();

  // Execute
  this._bsontype = 'BSONRegExp';
  this.pattern = pattern || '';
  this.options = options || '';

  // Validate options
  for(var i = 0; i < this.options.length; i++) {
    if(!(this.options[i] == 'i'
      || this.options[i] == 'm'
      || this.options[i] == 'x'
      || this.options[i] == 'l'
      || this.options[i] == 's'
      || this.options[i] == 'u'
    )) {
      throw new Error('the regular expression options [' + this.options[i] + "] is not supported");
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Binary"></a>[module mongoskin.Binary](#apidoc.module.mongoskin.Binary)

#### <a name="apidoc.element.mongoskin.Binary.Binary"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Binary (buffer, subType)](#apidoc.element.mongoskin.Binary.Binary)
- description and source-code
```javascript
function Binary(buffer, subType) {
  if(!(this instanceof Binary)) return new Binary(buffer, subType);

  this._bsontype = 'Binary';

  if(buffer instanceof Number) {
    this.sub_type = buffer;
    this.position = 0;
  } else {
    this.sub_type = subType == null ? BSON_BINARY_SUBTYPE_DEFAULT : subType;
    this.position = 0;
  }

  if(buffer != null && !(buffer instanceof Number)) {
    // Only accept Buffer, Uint8Array or Arrays
    if(typeof buffer == 'string') {
      // Different ways of writing the length of the string for the different types
      if(typeof Buffer != 'undefined') {
        this.buffer = new Buffer(buffer);
      } else if(typeof Uint8Array != 'undefined' || (Object.prototype.toString.call(buffer) == '[object Array]')) {
        this.buffer = writeStringToArray(buffer);
      } else {
        throw new Error("only String, Buffer, Uint8Array or Array accepted");
      }
    } else {
      this.buffer = buffer;
    }
    this.position = buffer.length;
  } else {
    if(typeof Buffer != 'undefined') {
      this.buffer =  new Buffer(Binary.BUFFER_SIZE);
    } else if(typeof Uint8Array != 'undefined'){
      this.buffer = new Uint8Array(new ArrayBuffer(Binary.BUFFER_SIZE));
    } else {
      this.buffer = new Array(Binary.BUFFER_SIZE);
    }
    // Set position to start of buffer
    this.position = 0;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Binary.prototype"></a>[module mongoskin.Binary.prototype](#apidoc.module.mongoskin.Binary.prototype)

#### <a name="apidoc.element.mongoskin.Binary.prototype.length"></a>[function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>length ()](#apidoc.element.mongoskin.Binary.prototype.length)
- description and source-code
```javascript
function length() {
  return this.position;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Binary.prototype.put"></a>[function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>put (byte_value)](#apidoc.element.mongoskin.Binary.prototype.put)
- description and source-code
```javascript
function put(byte_value) {
  // If it's a string and a has more than one character throw an error
  if(byte_value['length'] != null && typeof byte_value != 'number' && byte_value.length != 1) throw new Error("only accepts single
 character String, Uint8Array or Array");
  if(typeof byte_value != 'number' && byte_value < 0 || byte_value > 255) throw new Error("only accepts number in a valid unsigned
 byte range 0-255");

  // Decode the byte value once
  var decoded_byte = null;
  if(typeof byte_value == 'string') {
    decoded_byte = byte_value.charCodeAt(0);
  } else if(byte_value['length'] != null) {
    decoded_byte = byte_value[0];
  } else {
    decoded_byte = byte_value;
  }

  if(this.buffer.length > this.position) {
    this.buffer[this.position++] = decoded_byte;
  } else {
    if(typeof Buffer != 'undefined' && Buffer.isBuffer(this.buffer)) {
      // Create additional overflow buffer
      var buffer = new Buffer(Binary.BUFFER_SIZE + this.buffer.length);
      // Combine the two buffers together
      this.buffer.copy(buffer, 0, 0, this.buffer.length);
      this.buffer = buffer;
      this.buffer[this.position++] = decoded_byte;
    } else {
      var buffer = null;
      // Create a new buffer (typed or normal array)
      if(Object.prototype.toString.call(this.buffer) == '[object Uint8Array]') {
        buffer = new Uint8Array(new ArrayBuffer(Binary.BUFFER_SIZE + this.buffer.length));
      } else {
        buffer = new Array(Binary.BUFFER_SIZE + this.buffer.length);
      }

      // We need to copy all the content to the new array
      for(var i = 0; i < this.buffer.length; i++) {
        buffer[i] = this.buffer[i];
      }

      // Reassign the buffer
      this.buffer = buffer;
      // Write the byte
      this.buffer[this.position++] = decoded_byte;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Binary.prototype.read"></a>[function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>read (position, length)](#apidoc.element.mongoskin.Binary.prototype.read)
- description and source-code
```javascript
function read(position, length) {
  length = length && length > 0
    ? length
    : this.position;

  // Let's return the data based on the type we have
  if(this.buffer['slice']) {
    return this.buffer.slice(position, position + length);
  } else {
    // Create a buffer to keep the result
    var buffer = typeof Uint8Array != 'undefined' ? new Uint8Array(new ArrayBuffer(length)) : new Array(length);
    for(var i = 0; i < length; i++) {
      buffer[i] = this.buffer[position++];
    }
  }
  // Return the buffer
  return buffer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Binary.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Binary.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.buffer != null ? this.buffer.toString('base64') : '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Binary.prototype.toString"></a>[function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>toString (format)](#apidoc.element.mongoskin.Binary.prototype.toString)
- description and source-code
```javascript
toString = function (format) {
  return this.buffer != null ? this.buffer.slice(0, this.position).toString(format) : '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Binary.prototype.value"></a>[function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>value (asRaw)](#apidoc.element.mongoskin.Binary.prototype.value)
- description and source-code
```javascript
function value(asRaw) {
  asRaw = asRaw == null ? false : asRaw;

  // Optimize to serialize for the situation where the data == size of buffer
  if(asRaw && typeof Buffer != 'undefined' && Buffer.isBuffer(this.buffer) && this.buffer.length == this.position)
    return this.buffer;

  // If it's a node.js buffer object
  if(typeof Buffer != 'undefined' && Buffer.isBuffer(this.buffer)) {
    return asRaw ? this.buffer.slice(0, this.position) : this.buffer.toString('binary', 0, this.position);
  } else {
    if(asRaw) {
      // we support the slice command use it
      if(this.buffer['slice'] != null) {
        return this.buffer.slice(0, this.position);
      } else {
        // Create a new buffer to copy content to
        var newBuffer = Object.prototype.toString.call(this.buffer) == '[object Uint8Array]' ? new Uint8Array(new ArrayBuffer(this
.position)) : new Array(this.position);
        // Copy content
        for(var i = 0; i < this.position; i++) {
          newBuffer[i] = this.buffer[i];
        }
        // Return the buffer
        return newBuffer;
      }
    } else {
      return convertArraytoUtf8BinaryString(this.buffer, 0, this.position);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Binary.prototype.write"></a>[function <span class="apidocSignatureSpan">mongoskin.Binary.prototype.</span>write (string, offset)](#apidoc.element.mongoskin.Binary.prototype.write)
- description and source-code
```javascript
function write(string, offset) {
  offset = typeof offset == 'number' ? offset : this.position;

  // If the buffer is to small let's extend the buffer
  if(this.buffer.length < offset + string.length) {
    var buffer = null;
    // If we are in node.js
    if(typeof Buffer != 'undefined' && Buffer.isBuffer(this.buffer)) {
      buffer = new Buffer(this.buffer.length + string.length);
      this.buffer.copy(buffer, 0, 0, this.buffer.length);
    } else if(Object.prototype.toString.call(this.buffer) == '[object Uint8Array]') {
      // Create a new buffer
      buffer = new Uint8Array(new ArrayBuffer(this.buffer.length + string.length))
      // Copy the content
      for(var i = 0; i < this.position; i++) {
        buffer[i] = this.buffer[i];
      }
    }

    // Assign the new buffer
    this.buffer = buffer;
  }

  if(typeof Buffer != 'undefined' && Buffer.isBuffer(string) && Buffer.isBuffer(this.buffer)) {
    string.copy(this.buffer, offset, 0, string.length);
    this.position = (offset + string.length) > this.position ? (offset + string.length) : this.position;
    // offset = string.length
  } else if(typeof Buffer != 'undefined' && typeof string == 'string' && Buffer.isBuffer(this.buffer)) {
    this.buffer.write(string, offset, 'binary');
    this.position = (offset + string.length) > this.position ? (offset + string.length) : this.position;
    // offset = string.length;
  } else if(Object.prototype.toString.call(string) == '[object Uint8Array]'
    || Object.prototype.toString.call(string) == '[object Array]' && typeof string != 'string') {
    for(var i = 0; i < string.length; i++) {
      this.buffer[offset++] = string[i];
    }

    this.position = offset > this.position ? offset : this.position;
  } else if(typeof string == 'string') {
    for(var i = 0; i < string.length; i++) {
      this.buffer[offset++] = string.charCodeAt(i);
    }

    this.position = offset > this.position ? offset : this.position;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Chunk"></a>[module mongoskin.Chunk](#apidoc.module.mongoskin.Chunk)

#### <a name="apidoc.element.mongoskin.Chunk.Chunk"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Chunk (file, mongoObject, writeConcern)](#apidoc.element.mongoskin.Chunk.Chunk)
- description and source-code
```javascript
Chunk = function (file, mongoObject, writeConcern) {
  if(!(this instanceof Chunk)) return new Chunk(file, mongoObject);

  this.file = file;
  var mongoObjectFinal = mongoObject == null ? {} : mongoObject;
  this.writeConcern = writeConcern || {w:1};
  this.objectId = mongoObjectFinal._id == null ? new ObjectID() : mongoObjectFinal._id;
  this.chunkNumber = mongoObjectFinal.n == null ? 0 : mongoObjectFinal.n;
  this.data = new Binary();

  if(typeof mongoObjectFinal.data == "string") {
    var buffer = new Buffer(mongoObjectFinal.data.length);
    buffer.write(mongoObjectFinal.data, 0, mongoObjectFinal.data.length, 'binary');
    this.data = new Binary(buffer);
  } else if(Array.isArray(mongoObjectFinal.data)) {
    buffer = new Buffer(mongoObjectFinal.data.length);
    var data = mongoObjectFinal.data.join('');
    buffer.write(data, 0, data.length, 'binary');
    this.data = new Binary(buffer);
  } else if(mongoObjectFinal.data && mongoObjectFinal.data._bsontype === 'Binary') {
    this.data = mongoObjectFinal.data;
  } else if(!Buffer.isBuffer(mongoObjectFinal.data) && !(mongoObjectFinal.data == null)){
    throw Error("Illegal chunk format");
  }

  // Update position
  this.internalPosition = 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Chunk.prototype"></a>[module mongoskin.Chunk.prototype](#apidoc.module.mongoskin.Chunk.prototype)

#### <a name="apidoc.element.mongoskin.Chunk.prototype.buildMongoObject"></a>[function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>buildMongoObject (callback)](#apidoc.element.mongoskin.Chunk.prototype.buildMongoObject)
- description and source-code
```javascript
buildMongoObject = function (callback) {
  var mongoObject = {
    'files_id': this.file.fileId,
    'n': this.chunkNumber,
    'data': this.data};
  // If we are saving using a specific ObjectId
  if(this.objectId != null) mongoObject._id = this.objectId;

  callback(mongoObject);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Chunk.prototype.eof"></a>[function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>eof ()](#apidoc.element.mongoskin.Chunk.prototype.eof)
- description and source-code
```javascript
eof = function () {
  return this.internalPosition == this.length() ? true : false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Chunk.prototype.getc"></a>[function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>getc ()](#apidoc.element.mongoskin.Chunk.prototype.getc)
- description and source-code
```javascript
getc = function () {
  return this.read(1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Chunk.prototype.length"></a>[function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>length ()](#apidoc.element.mongoskin.Chunk.prototype.length)
- description and source-code
```javascript
length = function () {
  return this.data.length();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Chunk.prototype.read"></a>[function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>read (length)](#apidoc.element.mongoskin.Chunk.prototype.read)
- description and source-code
```javascript
read = function (length) {
  // Default to full read if no index defined
  length = length == null || length == 0 ? this.length() : length;

  if(this.length() - this.internalPosition + 1 >= length) {
    var data = this.data.read(this.internalPosition, length);
    this.internalPosition = this.internalPosition + length;
    return data;
  } else {
    return '';
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Chunk.prototype.readSlice"></a>[function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>readSlice (length)](#apidoc.element.mongoskin.Chunk.prototype.readSlice)
- description and source-code
```javascript
readSlice = function (length) {
  if ((this.length() - this.internalPosition) >= length) {
    var data = null;
    if (this.data.buffer != null) { //Pure BSON
      data = this.data.buffer.slice(this.internalPosition, this.internalPosition + length);
    } else { //Native BSON
      data = new Buffer(length);
      length = this.data.readInto(data, this.internalPosition);
    }
    this.internalPosition = this.internalPosition + length;
    return data;
  } else {
    return null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Chunk.prototype.rewind"></a>[function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>rewind ()](#apidoc.element.mongoskin.Chunk.prototype.rewind)
- description and source-code
```javascript
rewind = function () {
  this.internalPosition = 0;
  this.data = new Binary();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Chunk.prototype.save"></a>[function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>save (options, callback)](#apidoc.element.mongoskin.Chunk.prototype.save)
- description and source-code
```javascript
save = function (options, callback) {
  var self = this;
  if(typeof options == 'function') {
    callback = options;
    options = {};
  }

  self.file.chunkCollection(function(err, collection) {
    if(err) return callback(err);

    // Merge the options
    var writeOptions = { upsert: true };
    for(var name in options) writeOptions[name] = options[name];
    for(name in self.writeConcern) writeOptions[name] = self.writeConcern[name];

    if(self.data.length() > 0) {
      self.buildMongoObject(function(mongoObject) {
        var options = {forceServerObjectId:true};
        for(var name in self.writeConcern) {
          options[name] = self.writeConcern[name];
        }

        collection.replaceOne({'_id':self.objectId}, mongoObject, writeOptions, function(err) {
          callback(err, self);
        });
      });
    } else {
      callback(null, self);
    }
    // });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Chunk.prototype.write"></a>[function <span class="apidocSignatureSpan">mongoskin.Chunk.prototype.</span>write (data, callback)](#apidoc.element.mongoskin.Chunk.prototype.write)
- description and source-code
```javascript
write = function (data, callback) {
  this.data.write(data, this.internalPosition, data.length, 'binary');
  this.internalPosition = this.data.length();
  if(callback != null) return callback(null, this);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Code"></a>[module mongoskin.Code](#apidoc.module.mongoskin.Code)

#### <a name="apidoc.element.mongoskin.Code.Code"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Code (code, scope)](#apidoc.element.mongoskin.Code.Code)
- description and source-code
```javascript
function Code(code, scope) {
  if(!(this instanceof Code)) return new Code(code, scope);
  this._bsontype = 'Code';
  this.code = code;
  this.scope = scope;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Code.prototype"></a>[module mongoskin.Code.prototype](#apidoc.module.mongoskin.Code.prototype)

#### <a name="apidoc.element.mongoskin.Code.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.Code.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Code.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return {scope:this.scope, code:this.code};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Collection"></a>[module mongoskin.Collection](#apidoc.module.mongoskin.Collection)

#### <a name="apidoc.element.mongoskin.Collection.Collection"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Collection ()](#apidoc.element.mongoskin.Collection.Collection)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection._bindGetter"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.</span>_bindGetter (propName)](#apidoc.element.mongoskin.Collection._bindGetter)
- description and source-code
```javascript
_bindGetter = function (propName) {
    SkinClass.prototype.__defineGetter__(propName, function() {
        return this._native && this._native[propName];// || this['_prop_' + propName];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection._bindMethod"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.</span>_bindMethod (propName)](#apidoc.element.mongoskin.Collection._bindMethod)
- description and source-code
```javascript
_bindMethod = function (propName) {
  SkinClass.prototype[propName] = function() {
    var args = __slice.apply(arguments);
    if (this._state == STATE_OPEN) {
      this._native[propName].apply(this._native, args);
    } else {
      this.open(function(err, p_native) {
          if (err) {
            onError(err, args, skinClassName + '.' + propName);
          } else {
            p_native[propName].apply(p_native, args);
          }
      });
    }
    return this;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection._bindSetter"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.</span>_bindSetter (propName)](#apidoc.element.mongoskin.Collection._bindSetter)
- description and source-code
```javascript
_bindSetter = function (propName) {
    SkinClass.prototype.__defineSetter__(propName, function(value) {
        // this['_prop_' + propName] = value;
        this.open(function(err, p_native) {
            if(err) return onError(err, args, skinClassName + '.' + propName);
            p_native[propName] = value;
        });
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Collection.prototype"></a>[module mongoskin.Collection.prototype](#apidoc.module.mongoskin.Collection.prototype)

#### <a name="apidoc.element.mongoskin.Collection.prototype._close"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>_close (callback)](#apidoc.element.mongoskin.Collection.prototype._close)
- description and source-code
```javascript
_close = function (callback) {
  if(this._native.close) {
    this._native.close(callback)
  } else if(callback) {
    callback();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype._find"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>_find ()](#apidoc.element.mongoskin.Collection.prototype._find)
- description and source-code
```javascript
_find = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype._open"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>_open (callback)](#apidoc.element.mongoskin.Collection.prototype._open)
- description and source-code
```javascript
_open = function (callback) {
  var collection_args = this._collection_args.concat([callback]);
  this._skin_db.open(function(err, db) {
      if(err) return callback(err);
      db.collection.apply(db, collection_args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype._operateById"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>_operateById (methodName, id, args)](#apidoc.element.mongoskin.Collection.prototype._operateById)
- description and source-code
```javascript
_operateById = function (methodName, id, args) {
  args = __slice.call(args);
  args[0] = {_id: helper.toObjectID(id)};
  this[methodName].apply(this, args);
  return this;
}
```
- example usage
```shell
...
*
* @param {String|ObjectID|Number} id, doc primary key '_id'
* @param {Function(err, doc)} callback
* @return {SkinCollection} this
* @api public
*/
SkinCollection.prototype.findById = function (id, callback) {
 return this._operateById('findOne', id, arguments);
};

/**
* Update doc by _id.
* @param {String|ObjectID|Number} id, doc primary key '_id'
* @param {Object} doc
* @param {Function(err)} callback
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.aggregate"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>aggregate ()](#apidoc.element.mongoskin.Collection.prototype.aggregate)
- description and source-code
```javascript
aggregate = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.bind"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>bind (extendObject)](#apidoc.element.mongoskin.Collection.prototype.bind)
- description and source-code
```javascript
bind = function (extendObject) {
  for(var key in extendObject) {
    if(typeof extendObject[key] == 'function') {
      this[key] = extendObject[key].bind(this);
    } else {
      this[key] = extendObject[key];
    }
  }
}
```
- example usage
```shell
...
========

Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.bulkWrite"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>bulkWrite ()](#apidoc.element.mongoskin.Collection.prototype.bulkWrite)
- description and source-code
```javascript
bulkWrite = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>close (callback)](#apidoc.element.mongoskin.Collection.prototype.close)
- description and source-code
```javascript
close = function (callback) {
  if (this._state === STATE_CLOSE) {
    callback && callback();
  } else if (this._state === STATE_OPEN) {
    this._state = STATE_CLOSE;
    this._close(callback);
  } else if (this._state === STATE_OPENNING) {
    var self = this;
    this._emitter.once('open', function (err, db) {
        self.close(callback);
    });
  }
  this._native = null;
  return this;
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.count"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>count ()](#apidoc.element.mongoskin.Collection.prototype.count)
- description and source-code
```javascript
count = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.createIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>createIndex ()](#apidoc.element.mongoskin.Collection.prototype.createIndex)
- description and source-code
```javascript
createIndex = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.createIndexes"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>createIndexes ()](#apidoc.element.mongoskin.Collection.prototype.createIndexes)
- description and source-code
```javascript
createIndexes = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.deleteMany"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>deleteMany ()](#apidoc.element.mongoskin.Collection.prototype.deleteMany)
- description and source-code
```javascript
deleteMany = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.deleteOne"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>deleteOne ()](#apidoc.element.mongoskin.Collection.prototype.deleteOne)
- description and source-code
```javascript
deleteOne = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.distinct"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>distinct ()](#apidoc.element.mongoskin.Collection.prototype.distinct)
- description and source-code
```javascript
distinct = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.drop"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>drop ()](#apidoc.element.mongoskin.Collection.prototype.drop)
- description and source-code
```javascript
drop = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.dropAllIndexes"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>dropAllIndexes ()](#apidoc.element.mongoskin.Collection.prototype.dropAllIndexes)
- description and source-code
```javascript
dropAllIndexes = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.dropIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>dropIndex ()](#apidoc.element.mongoskin.Collection.prototype.dropIndex)
- description and source-code
```javascript
dropIndex = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.dropIndexes"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>dropIndexes ()](#apidoc.element.mongoskin.Collection.prototype.dropIndexes)
- description and source-code
```javascript
dropIndexes = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.ensureIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>ensureIndex ()](#apidoc.element.mongoskin.Collection.prototype.ensureIndex)
- description and source-code
```javascript
ensureIndex = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.find"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>find (query, options, callback)](#apidoc.element.mongoskin.Collection.prototype.find)
- description and source-code
```javascript
find = function (query, options, callback) {
  var args = __slice.call(arguments);
  if(this.isOpen()) {
    return this._native.find.apply(this._native, args);
  }
  if (args.length > 0 && typeof args[args.length - 1] === 'function') {
    this._find.apply(this, args);
    return this;
  } else {
    var cursor = new SkinCursor();
    cursor._skin_collection = this;
    cursor._find_args = args;
    return cursor;
  }
}
```
- example usage
```shell
...

Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.findAndModify"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findAndModify ()](#apidoc.element.mongoskin.Collection.prototype.findAndModify)
- description and source-code
```javascript
findAndModify = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.findAndRemove"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findAndRemove ()](#apidoc.element.mongoskin.Collection.prototype.findAndRemove)
- description and source-code
```javascript
findAndRemove = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.findById"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findById (id, callback)](#apidoc.element.mongoskin.Collection.prototype.findById)
- description and source-code
```javascript
findById = function (id, callback) {
  return this._operateById('findOne', id, arguments);
}
```
- example usage
```shell
...
alias 'new Admin(db, ...)'
### db.grid(...)
alias 'new Grid(db, ...)'
### db.gridStore(...)
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.findEach"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findEach (query, options, eachCallback)](#apidoc.element.mongoskin.Collection.prototype.findEach)
- description and source-code
```javascript
findEach = function (query, options, eachCallback) {
  var args = __slice.call(arguments);
  var fn = args[args.length - 1];
  args[args.length - 1] = function (err, cursor) {
    if (err) {
      return fn(err);
    }
    cursor.each(fn);
  };
  this.find.apply(this, args);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.findItems"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findItems (query, options, callback)](#apidoc.element.mongoskin.Collection.prototype.findItems)
- description and source-code
```javascript
findItems = function (query, options, callback) {
  var args = __slice.call(arguments);
  var fn = args[args.length - 1];
  args[args.length - 1] = function (err, cursor) {
    if (err) {
      return fn(err);
    }
    cursor.toArray(fn);
  };
  this.find.apply(this, args);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.findOne"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findOne ()](#apidoc.element.mongoskin.Collection.prototype.findOne)
- description and source-code
```javascript
findOne = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
...
Model helper:

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article').bind({
    getByAuthor: function(author_id, callback) {
        this.findOne({author_id: author_id}, callback);
    }
});
db.article.getByAuthor(author_id, function(err, article) {
        console.log(article);
});
'''
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.findOneAndDelete"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findOneAndDelete ()](#apidoc.element.mongoskin.Collection.prototype.findOneAndDelete)
- description and source-code
```javascript
findOneAndDelete = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.findOneAndReplace"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findOneAndReplace ()](#apidoc.element.mongoskin.Collection.prototype.findOneAndReplace)
- description and source-code
```javascript
findOneAndReplace = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.findOneAndUpdate"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>findOneAndUpdate ()](#apidoc.element.mongoskin.Collection.prototype.findOneAndUpdate)
- description and source-code
```javascript
findOneAndUpdate = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.geoHaystackSearch"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>geoHaystackSearch ()](#apidoc.element.mongoskin.Collection.prototype.geoHaystackSearch)
- description and source-code
```javascript
geoHaystackSearch = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.geoNear"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>geoNear ()](#apidoc.element.mongoskin.Collection.prototype.geoNear)
- description and source-code
```javascript
geoNear = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.group"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>group ()](#apidoc.element.mongoskin.Collection.prototype.group)
- description and source-code
```javascript
group = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.indexExists"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>indexExists ()](#apidoc.element.mongoskin.Collection.prototype.indexExists)
- description and source-code
```javascript
indexExists = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.indexInformation"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>indexInformation ()](#apidoc.element.mongoskin.Collection.prototype.indexInformation)
- description and source-code
```javascript
indexInformation = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.indexes"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>indexes ()](#apidoc.element.mongoskin.Collection.prototype.indexes)
- description and source-code
```javascript
indexes = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.initializeOrderedBulkOp"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>initializeOrderedBulkOp ()](#apidoc.element.mongoskin.Collection.prototype.initializeOrderedBulkOp)
- description and source-code
```javascript
initializeOrderedBulkOp = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.initializeUnorderedBulkOp"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>initializeUnorderedBulkOp ()](#apidoc.element.mongoskin.Collection.prototype.initializeUnorderedBulkOp)
- description and source-code
```javascript
initializeUnorderedBulkOp = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.insert"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>insert ()](#apidoc.element.mongoskin.Collection.prototype.insert)
- description and source-code
```javascript
insert = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.insertMany"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>insertMany ()](#apidoc.element.mongoskin.Collection.prototype.insertMany)
- description and source-code
```javascript
insertMany = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.insertOne"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>insertOne ()](#apidoc.element.mongoskin.Collection.prototype.insertOne)
- description and source-code
```javascript
insertOne = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.isCapped"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>isCapped ()](#apidoc.element.mongoskin.Collection.prototype.isCapped)
- description and source-code
```javascript
isCapped = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.isOpen"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>isOpen ()](#apidoc.element.mongoskin.Collection.prototype.isOpen)
- description and source-code
```javascript
isOpen = function () {
  return this._state === STATE_OPEN;
}
```
- example usage
```shell
...
 * @param {Function(err, docs)} callback
 * @return {SkinCursor|SkinCollection} if last argument is not a function, then returns a SkinCursor,
 *   otherise return this
 * @api public
 */
SkinCollection.prototype.find = function (query, options, callback) {
var args = __slice.call(arguments);
if(this.isOpen()) {
  return this._native.find.apply(this._native, args);
}
if (args.length > 0 && typeof args[args.length - 1] === 'function') {
  this._find.apply(this, args);
  return this;
} else {
  var cursor = new SkinCursor();
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.listIndexes"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>listIndexes ()](#apidoc.element.mongoskin.Collection.prototype.listIndexes)
- description and source-code
```javascript
listIndexes = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.mapReduce"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>mapReduce ()](#apidoc.element.mongoskin.Collection.prototype.mapReduce)
- description and source-code
```javascript
mapReduce = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.open"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>open (callback)](#apidoc.element.mongoskin.Collection.prototype.open)
- description and source-code
```javascript
open = function (callback) {
  switch (this._state) {
    case STATE_OPEN:
      callback(null, this._native);
      break;
    case STATE_OPENNING:
      this._emitter.once('open', callback);
      break;
    default:
      this._emitter.once('open', callback);
      this._state = STATE_OPENNING;
      var self = this;
      this._open(function(err, p_native) {
          if (err) {
            self._state = STATE_CLOSE;
          } else {
            self._state = STATE_OPEN;
            self._native = p_native;
          }
          self._emitter.emit('open', err, p_native);
      });
  }
  return this;
}
```
- example usage
```shell
...

alias origin 'db.collection(..., function(err, collection) {....})'

origin:

'''js
var db = new Db(...);
db.open(function(err, db) {
    db.collection('myCollection', {strict: true}, function(err, myCollection) {
        // myCollection.find() ...
    });
});
'''

mongoskin:
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.options"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>options ()](#apidoc.element.mongoskin.Collection.prototype.options)
- description and source-code
```javascript
options = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.parallelCollectionScan"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>parallelCollectionScan ()](#apidoc.element.mongoskin.Collection.prototype.parallelCollectionScan)
- description and source-code
```javascript
parallelCollectionScan = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.reIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>reIndex ()](#apidoc.element.mongoskin.Collection.prototype.reIndex)
- description and source-code
```javascript
reIndex = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.remove"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>remove ()](#apidoc.element.mongoskin.Collection.prototype.remove)
- description and source-code
```javascript
remove = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
...
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native

### Removed API from mongoskin 1.3.20
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.removeById"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>removeById (id, callback)](#apidoc.element.mongoskin.Collection.prototype.removeById)
- description and source-code
```javascript
removeById = function (id, callback) {
  var oldCb = callback;
  var _this = this;
  if (callback) {
    callback = function(error, res) {
      oldCb.call(_this, error, !!res ? res.result.n : null);
    };
  }
  return this._operateById('remove', id, [id, callback]);
}
```
- example usage
```shell
...
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native

### Removed API from mongoskin 1.3.20
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.removeMany"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>removeMany ()](#apidoc.element.mongoskin.Collection.prototype.removeMany)
- description and source-code
```javascript
removeMany = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.removeOne"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>removeOne ()](#apidoc.element.mongoskin.Collection.prototype.removeOne)
- description and source-code
```javascript
removeOne = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.rename"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>rename ()](#apidoc.element.mongoskin.Collection.prototype.rename)
- description and source-code
```javascript
rename = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.replaceOne"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>replaceOne ()](#apidoc.element.mongoskin.Collection.prototype.replaceOne)
- description and source-code
```javascript
replaceOne = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.save"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>save ()](#apidoc.element.mongoskin.Collection.prototype.save)
- description and source-code
```javascript
save = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.stats"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>stats ()](#apidoc.element.mongoskin.Collection.prototype.stats)
- description and source-code
```javascript
stats = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.update"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>update ()](#apidoc.element.mongoskin.Collection.prototype.update)
- description and source-code
```javascript
update = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
...
### db.gridStore(...)
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.updateById"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>updateById (id, doc, callback)](#apidoc.element.mongoskin.Collection.prototype.updateById)
- description and source-code
```javascript
updateById = function (id, doc, callback) {
  var oldCb = callback;
  var _this = this;
  if (callback) {
    callback = function(error, res) {
      oldCb.call(_this, error, !!res ? res.result : null);
    };
  }
  return this._operateById('update', id, [id, doc, callback]);
}
```
- example usage
```shell
...
alias 'new Grid(db, ...)'
### db.gridStore(...)
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native
...
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.updateMany"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>updateMany ()](#apidoc.element.mongoskin.Collection.prototype.updateMany)
- description and source-code
```javascript
updateMany = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Collection.prototype.updateOne"></a>[function <span class="apidocSignatureSpan">mongoskin.Collection.prototype.</span>updateOne ()](#apidoc.element.mongoskin.Collection.prototype.updateOne)
- description and source-code
```javascript
updateOne = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.CoreConnection"></a>[module mongoskin.CoreConnection](#apidoc.module.mongoskin.CoreConnection)

#### <a name="apidoc.element.mongoskin.CoreConnection.CoreConnection"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>CoreConnection (messageHandler, options)](#apidoc.element.mongoskin.CoreConnection.CoreConnection)
- description and source-code
```javascript
CoreConnection = function (messageHandler, options) {
  // Add event listener
  EventEmitter.call(this);
  // Set empty if no options passed
  this.options = options || {};
  // Identification information
  this.id = _id++;
  // Logger instance
  this.logger = Logger('Connection', options);
  // No bson parser passed in
  if(!options.bson) throw new Error("must pass in valid bson parser");
  // Get bson parser
  this.bson = options.bson;
  // Grouping tag used for debugging purposes
  this.tag = options.tag;
  // Message handler
  this.messageHandler = messageHandler;

  // Max BSON message size
  this.maxBsonMessageSize = options.maxBsonMessageSize || (1024 * 1024 * 16 * 4);
  // Debug information
  if(this.logger.isDebug()) this.logger.debug(f('creating connection %s with options [%s]', this.id, JSON.stringify(debugOptions
(debugFields, options))));

  // Default options
  this.port = options.port || 27017;
  this.host = options.host || 'localhost';
  this.keepAlive = typeof options.keepAlive == 'boolean' ? options.keepAlive : true;
  this.keepAliveInitialDelay = options.keepAliveInitialDelay || 0;
  this.noDelay = typeof options.noDelay == 'boolean' ? options.noDelay : true;
  this.connectionTimeout = options.connectionTimeout || 0;
  this.socketTimeout = options.socketTimeout || 0;

  // If connection was destroyed
  this.destroyed = false;

  // Check if we have a domain socket
  this.domainSocket = this.host.indexOf('\/') != -1;

  // Serialize commands using function
  this.singleBufferSerializtion = typeof options.singleBufferSerializtion == 'boolean' ? options.singleBufferSerializtion : true
;
  this.serializationFunction = this.singleBufferSerializtion ? 'toBinUnified' : 'toBin';

  // SSL options
  this.ca = options.ca || null;
  this.crl = options.crl || null;
  this.cert = options.cert || null;
  this.key = options.key || null;
  this.passphrase = options.passphrase || null;
  this.ssl = typeof options.ssl == 'boolean' ? options.ssl : false;
  this.rejectUnauthorized = typeof options.rejectUnauthorized == 'boolean' ? options.rejectUnauthorized : true;
  this.checkServerIdentity = typeof options.checkServerIdentity == 'boolean'
    || typeof options.checkServerIdentity == 'function' ? options.checkServerIdentity : true;

  // If ssl not enabled
  if(!this.ssl) this.rejectUnauthorized = false;

  // Response options
  this.responseOptions = {
    promoteLongs: typeof options.promoteLongs == 'boolean' ?  options.promoteLongs : true,
    promoteValues: typeof options.promoteValues == 'boolean' ? options.promoteValues : true,
    promoteBuffers: typeof options.promoteBuffers == 'boolean' ? options.promoteBuffers: false
  }

  // Flushing
  this.flushing = false;
  this.queue = [];

  // Internal state
  this.connection = null;
  this.writeStream = null;

  // Create hash method
  var hash = crypto.createHash('sha1');
  hash.update(f('%s:%s', this.host, this.port));

  // Create a hash name
  this.hashedName = hash.digest('hex');

  // All operations in flight on the connection
  this.workItems = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection.connections"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.</span>connections ()](#apidoc.element.mongoskin.CoreConnection.connections)
- description and source-code
```javascript
connections = function () {
  return connections;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection.disableConnectionAccounting"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.</span>disableConnectionAccounting ()](#apidoc.element.mongoskin.CoreConnection.disableConnectionAccounting)
- description and source-code
```javascript
disableConnectionAccounting = function () {
  connectionAccounting = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection.enableConnectionAccounting"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.</span>enableConnectionAccounting ()](#apidoc.element.mongoskin.CoreConnection.enableConnectionAccounting)
- description and source-code
```javascript
enableConnectionAccounting = function () {
  connectionAccounting = true;
  connections = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection.super_"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.</span>super_ ()](#apidoc.element.mongoskin.CoreConnection.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.CoreConnection.prototype"></a>[module mongoskin.CoreConnection.prototype](#apidoc.module.mongoskin.CoreConnection.prototype)

#### <a name="apidoc.element.mongoskin.CoreConnection.prototype.connect"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>connect (_options)](#apidoc.element.mongoskin.CoreConnection.prototype.connect)
- description and source-code
```javascript
connect = function (_options) {
  var self = this;
  _options = _options || {};
  // Set the connections
  if(connectionAccounting) addConnection(this.id, this);
  // Check if we are overriding the promoteLongs
  if(typeof _options.promoteLongs == 'boolean') {
    self.responseOptions.promoteLongs = _options.promoteLongs;
    self.responseOptions.promoteValues = _options.promoteValues;
    self.responseOptions.promoteBuffers = _options.promoteBuffers;
  }

  // Create new connection instance
  self.connection = self.domainSocket
    ? net.createConnection(self.host)
    : net.createConnection(self.port, self.host);

  // Set the options for the connection
  self.connection.setKeepAlive(self.keepAlive, self.keepAliveInitialDelay);
  self.connection.setTimeout(self.connectionTimeout);
  self.connection.setNoDelay(self.noDelay);

  // If we have ssl enabled
  if(self.ssl) {
    var sslOptions = {
        socket: self.connection
      , rejectUnauthorized: self.rejectUnauthorized
    }

    // Merge in options
    merge(sslOptions, this.options);
    merge(sslOptions, _options);

    // Set options for ssl
    if(self.ca) sslOptions.ca = self.ca;
    if(self.crl) sslOptions.crl = self.crl;
    if(self.cert) sslOptions.cert = self.cert;
    if(self.key) sslOptions.key = self.key;
    if(self.passphrase) sslOptions.passphrase = self.passphrase;

    // Override checkServerIdentity behavior
    if(self.checkServerIdentity == false) {
      // Skip the identiy check by retuning undefined as per node documents
      // https://nodejs.org/api/tls.html#tls_tls_connect_options_callback
      sslOptions.checkServerIdentity = function() {
        return undefined;
      }
    } else if(typeof self.checkServerIdentity == 'function') {
      sslOptions.checkServerIdentity = self.checkServerIdentity;
    }

    // Set default sni servername to be the same as host
    if(sslOptions.servername == null) {
      sslOptions.servername = self.host;
    }

    // Attempt SSL connection
    self.connection = tls.connect(self.port, self.host, sslOptions, function() {
      // Error on auth or skip
      if(self.connection.authorizationError && self.rejectUnauthorized) {
        return self.emit("error", self.connection.authorizationError, self, {ssl:true});
      }

      // Set socket timeout instead of connection timeout
      self.connection.setTimeout(self.socketTimeout);
      // We are done emit connect
      self.emit('connect', self);
    });
    self.connection.setTimeout(self.connectionTimeout);
  } else {
    self.connection.on('connect', function() {
      // Set socket timeout instead of connection timeout
      self.connection.setTimeout(self.socketTimeout);
      // Emit connect event
      self.emit('connect', self);
    });
  }

  // Add handlers for events
  self.connection.once('error', errorHandler(self));
  self.connection.once('timeout', timeoutHandler(self));
  self.connection.once('close', closeHandler(self));
  self.connection.on('data', dataHandler(self));
}
```
- example usage
```shell
...
var Db = mongo.Db;
var Server = mongo.Server;
var MongoClient = mongo.MongoClient;
var ReplSetServers = mongo.ReplSetServers;
...
'''

### MongoClient.connect(...)

returns a 'Db' instance

alias origin 'MongoClient.connect(..., function(err, db) { .... })'

origin:
...
```

#### <a name="apidoc.element.mongoskin.CoreConnection.prototype.destroy"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>destroy ()](#apidoc.element.mongoskin.CoreConnection.prototype.destroy)
- description and source-code
```javascript
destroy = function () {
  // Set the connections
  if(connectionAccounting) deleteConnection(this.id);
  if(this.connection) {
    this.connection.end();
    this.connection.destroy();
  }

  this.destroyed = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection.prototype.isConnected"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>isConnected ()](#apidoc.element.mongoskin.CoreConnection.prototype.isConnected)
- description and source-code
```javascript
isConnected = function () {
  if(this.destroyed) return false;
  return !this.connection.destroyed && this.connection.writable;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection.prototype.resetSocketTimeout"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>resetSocketTimeout ()](#apidoc.element.mongoskin.CoreConnection.prototype.resetSocketTimeout)
- description and source-code
```javascript
resetSocketTimeout = function () {
  if(this.connection) {
    this.connection.setTimeout(this.socketTimeout);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection.prototype.setSocketTimeout"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>setSocketTimeout (value)](#apidoc.element.mongoskin.CoreConnection.prototype.setSocketTimeout)
- description and source-code
```javascript
setSocketTimeout = function (value) {
  if(this.connection) {
    this.connection.setTimeout(value);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>toJSON ()](#apidoc.element.mongoskin.CoreConnection.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return {id: this.id, host: this.host, port: this.port};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection.prototype.toString"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>toString ()](#apidoc.element.mongoskin.CoreConnection.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return "" + this.id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection.prototype.unref"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>unref ()](#apidoc.element.mongoskin.CoreConnection.prototype.unref)
- description and source-code
```javascript
unref = function () {
  if (this.connection) this.connection.unref();
  else {
    var self = this;
    this.once('connect', function() {
      self.connection.unref();
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreConnection.prototype.write"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreConnection.prototype.</span>write (buffer)](#apidoc.element.mongoskin.CoreConnection.prototype.write)
- description and source-code
```javascript
write = function (buffer) {
  var i;
  // Debug Log
  if(this.logger.isDebug()) {
    if(!Array.isArray(buffer)) {
      this.logger.debug(f('writing buffer [%s] to %s:%s', buffer.toString('hex'), this.host, this.port));
    } else {
      for(i = 0; i < buffer.length; i++)
        this.logger.debug(f('writing buffer [%s] to %s:%s', buffer[i].toString('hex'), this.host, this.port));
    }
  }

  // Write out the command
  if(!Array.isArray(buffer)) return this.connection.write(buffer, 'binary');
  // Iterate over all buffers and write them in order to the socket
  for(i = 0; i < buffer.length; i++) this.connection.write(buffer[i], 'binary');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.CoreServer"></a>[module mongoskin.CoreServer](#apidoc.module.mongoskin.CoreServer)

#### <a name="apidoc.element.mongoskin.CoreServer.CoreServer"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>CoreServer (options)](#apidoc.element.mongoskin.CoreServer.CoreServer)
- description and source-code
```javascript
CoreServer = function (options) {
  options = options || {};

  // Add event listener
  EventEmitter.call(this);

  // Server instance id
  this.id = id++;

  // Internal state
  this.s = {
    // Options
    options: options,
    // Logger
    logger: Logger('Server', options),
    // Factory overrides
    Cursor: options.cursorFactory || BasicCursor,
    // BSON instance
    bson: options.bson || new BSON([BSON.Binary, BSON.Code, BSON.DBRef, BSON.Decimal128,
      BSON.Double, BSON.Int32, BSON.Long, BSON.Map, BSON.MaxKey, BSON.MinKey,
      BSON.ObjectId, BSON.BSONRegExp, BSON.Symbol, BSON.Timestamp]),
    // Pool
    pool: null,
    // Disconnect handler
    disconnectHandler: options.disconnectHandler,
    // Monitor thread (keeps the connection alive)
    monitoring: typeof options.monitoring == 'boolean' ? options.monitoring : true,
    // Is the server in a topology
    inTopology: typeof options.inTopology == 'boolean' ? options.inTopology : false,
    // Monitoring timeout
    monitoringInterval: typeof options.monitoringInterval == 'number'
      ? options.monitoringInterval
      : 5000,
    // Topology id
    topologyId: -1
  }

  // Curent ismaster
  this.ismaster = null;
  // Current ping time
  this.lastIsMasterMS = -1;
  // The monitoringProcessId
  this.monitoringProcessId = null;
  // Initial connection
  this.initalConnect = true;
  // Wire protocol handler, default to oldest known protocol handler
  // this gets changed when the first ismaster is called.
  this.wireProtocolHandler = new PreTwoSixWireProtocolSupport();
  // Default type
  this._type = 'server';
  // Set the client info
  this.clientInfo = createClientInfo(options);

  // Max Stalleness values
  // last time we updated the ismaster state
  this.lastUpdateTime = 0;
  // Last write time
  this.lastWriteDate = 0;
  // Stalleness
  this.staleness = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.disableServerAccounting"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.</span>disableServerAccounting ()](#apidoc.element.mongoskin.CoreServer.disableServerAccounting)
- description and source-code
```javascript
disableServerAccounting = function () {
  serverAccounting = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.enableServerAccounting"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.</span>enableServerAccounting ()](#apidoc.element.mongoskin.CoreServer.enableServerAccounting)
- description and source-code
```javascript
enableServerAccounting = function () {
  serverAccounting = true;
  servers = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.servers"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.</span>servers ()](#apidoc.element.mongoskin.CoreServer.servers)
- description and source-code
```javascript
servers = function () {
  return servers;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.super_"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.</span>super_ ()](#apidoc.element.mongoskin.CoreServer.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.CoreServer.prototype"></a>[module mongoskin.CoreServer.prototype](#apidoc.module.mongoskin.CoreServer.prototype)

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.auth"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>auth (mechanism, db)](#apidoc.element.mongoskin.CoreServer.prototype.auth)
- description and source-code
```javascript
auth = function (mechanism, db) {
  var self = this;

  // If we have the default mechanism we pick mechanism based on the wire
  // protocol max version. If it's >= 3 then scram-sha1 otherwise mongodb-cr
  if(mechanism == 'default' && self.ismaster && self.ismaster.maxWireVersion >= 3) {
    mechanism = 'scram-sha-1';
  } else if(mechanism == 'default') {
    mechanism = 'mongocr';
  }

  // Slice all the arguments off
  var args = Array.prototype.slice.call(arguments, 0);
  // Set the mechanism
  args[0] = mechanism;
  // Get the callback
  var callback = args[args.length - 1];

  // If we are not connected or have a disconnectHandler specified
  if(disconnectHandler(self, 'auth', db, args, {}, callback)) {
    return;
  }

  // Do not authenticate if we are an arbiter
  if(this.lastIsMaster() && this.lastIsMaster().arbiterOnly) {
    return callback(null, true);
  }

  // Apply the arguments to the pool
  self.s.pool.auth.apply(self.s.pool, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.command"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>command (ns, cmd, options, callback)](#apidoc.element.mongoskin.CoreServer.prototype.command)
- description and source-code
```javascript
command = function (ns, cmd, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {}, options = options || {};
  var result = basicReadValidations(self, options);
  if(result) return callback(result);

  // Debug log
  if(self.s.logger.isDebug()) self.s.logger.debug(f('executing command [%s] against %s', JSON.stringify({
    ns: ns, cmd: cmd, options: debugOptions(debugFields, options)
  }), self.name));

  // If we are not connected or have a disconnectHandler specified
  if(disconnectHandler(self, 'command', ns, cmd, options, callback)) return;

  // Check if we have collation support
  if(this.ismaster && this.ismaster.maxWireVersion < 5 && cmd.collation) {
    return callback(new MongoError(f('server %s does not support collation', this.name)));
  }

  // Query options
  var queryOptions = {
    numberToSkip: 0,
    numberToReturn: -1,
    checkKeys: typeof options.checkKeys == 'boolean' ? options.checkKeys: false,
    serializeFunctions: typeof options.serializeFunctions == 'boolean' ? options.serializeFunctions : false,
    ignoreUndefined: typeof options.ignoreUndefined == 'boolean' ? options.ignoreUndefined : false
  };

  // Are we executing against a specific topology
  var topology = options.topology || {};
  // Create the query object
  var query = self.wireProtocolHandler.command(self.s.bson, ns, cmd, {}, topology, options);
  // Set slave OK of the query
  query.slaveOk = options.readPreference ? options.readPreference.slaveOk() : false;

  // Write options
  var writeOptions = {
    raw: typeof options.raw == 'boolean' ? options.raw : false,
    promoteLongs: typeof options.promoteLongs == 'boolean' ? options.promoteLongs : true,
    promoteValues: typeof options.promoteValues == 'boolean' ? options.promoteValues : true,
    promoteBuffers: typeof options.promoteBuffers == 'boolean' ? options.promoteBuffers : false,
    command: true,
    monitoring: typeof options.monitoring == 'boolean' ? options.monitoring : false,
    fullResult: typeof options.fullResult == 'boolean' ? options.fullResult : false,
    requestId: query.requestId,
    socketTimeout: typeof options.socketTimeout == 'number' ? options.socketTimeout : null,
  };

  // Write the operation to the pool
  self.s.pool.write(query, writeOptions, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.connect"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>connect (options)](#apidoc.element.mongoskin.CoreServer.prototype.connect)
- description and source-code
```javascript
connect = function (options) {
  var self = this;
  options = options || {};

  // Set the connections
  if(serverAccounting) servers[this.id] = this;

  // Do not allow connect to be called on anything that's not disconnected
  if(self.s.pool && !self.s.pool.isDisconnected() && !self.s.pool.isDestroyed()) {
    throw MongoError.create(f('server instance in invalid state %s', self.s.state));
  }

  // Create a pool
  self.s.pool = new Pool(assign(self.s.options, options, {bson: this.s.bson}));

  // Set up listeners
  self.s.pool.on('close', eventHandler(self, 'close'));
  self.s.pool.on('error', eventHandler(self, 'error'));
  self.s.pool.on('timeout', eventHandler(self, 'timeout'));
  self.s.pool.on('parseError', eventHandler(self, 'parseError'));
  self.s.pool.on('connect', eventHandler(self, 'connect'));
  self.s.pool.on('reconnect', eventHandler(self, 'reconnect'));
  self.s.pool.on('reconnectFailed', eventHandler(self, 'reconnectFailed'));

  // Emit toplogy opening event if not in topology
  if(!self.s.inTopology) {
    this.emit('topologyOpening', { topologyId: self.id });
  }

  // Emit opening server event
  self.emit('serverOpening', {
    topologyId: self.s.topologyId != -1 ? self.s.topologyId : self.id,
    address: self.name
  });

  // Connect with optional auth settings
  if(options.auth) {
    self.s.pool.connect.apply(self.s.pool, options.auth);
  } else {
    self.s.pool.connect();
  }
}
```
- example usage
```shell
...
var Db = mongo.Db;
var Server = mongo.Server;
var MongoClient = mongo.MongoClient;
var ReplSetServers = mongo.ReplSetServers;
...
'''

### MongoClient.connect(...)

returns a 'Db' instance

alias origin 'MongoClient.connect(..., function(err, db) { .... })'

origin:
...
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.connections"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>connections ()](#apidoc.element.mongoskin.CoreServer.prototype.connections)
- description and source-code
```javascript
connections = function () {
  return this.s.pool.allConnections();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.cursor"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>cursor (ns, cmd, cursorOptions)](#apidoc.element.mongoskin.CoreServer.prototype.cursor)
- description and source-code
```javascript
cursor = function (ns, cmd, cursorOptions) {
  var s = this.s;
  cursorOptions = cursorOptions || {};
  // Set up final cursor type
  var FinalCursor = cursorOptions.cursorFactory || s.Cursor;
  // Return the cursor
  return new FinalCursor(s.bson, ns, cmd, cursorOptions, this, s.options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.destroy"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>destroy (options)](#apidoc.element.mongoskin.CoreServer.prototype.destroy)
- description and source-code
```javascript
destroy = function (options) {
  options = options || {};
  var self = this;

  // Set the connections
  if(serverAccounting) delete servers[this.id];

  // Destroy the monitoring process if any
  if(this.monitoringProcessId) {
    clearTimeout(this.monitoringProcessId);
  }

  // No pool, return
  if(!self.s.pool) return;

  // Emit close event
  if(options.emitClose) {
    self.emit('close', self);
  }

  // Emit destroy event
  if(options.emitDestroy) {
    self.emit('destroy', self);
  }

  // Remove all listeners
  listeners.forEach(function(event) {
    self.s.pool.removeAllListeners(event);
  });

  // Emit opening server event
  if(self.listeners('serverClosed').length > 0) self.emit('serverClosed', {
    topologyId: self.s.topologyId != -1 ? self.s.topologyId : self.id, address: self.name
  });

  // Emit toplogy opening event if not in topology
  if(self.listeners('topologyClosed').length > 0 && !self.s.inTopology) {
    self.emit('topologyClosed', { topologyId: self.id });
  }

  if(self.s.logger.isDebug()) {
    self.s.logger.debug(f('destroy called on server %s', self.name));
  }

  // Destroy the pool
  this.s.pool.destroy(options.force);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.equals"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>equals (server)](#apidoc.element.mongoskin.CoreServer.prototype.equals)
- description and source-code
```javascript
equals = function (server) {
  if(typeof server == 'string') return this.name.toLowerCase() == server.toLowerCase();
  if(server.name) return this.name.toLowerCase() == server.name.toLowerCase();
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.getConnection"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>getConnection ()](#apidoc.element.mongoskin.CoreServer.prototype.getConnection)
- description and source-code
```javascript
getConnection = function () {
  return this.s.pool.get();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.getDescription"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>getDescription ()](#apidoc.element.mongoskin.CoreServer.prototype.getDescription)
- description and source-code
```javascript
getDescription = function () {
  var ismaster = this.ismaster || {};
  var description = {
    type: sdam.getTopologyType(this),
    address: this.name,
  };

  // Add fields if available
  if(ismaster.hosts) description.hosts = ismaster.hosts;
  if(ismaster.arbiters) description.arbiters = ismaster.arbiters;
  if(ismaster.passives) description.passives = ismaster.passives;
  if(ismaster.setName) description.setName = ismaster.setName;
  return description;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.getServer"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>getServer ()](#apidoc.element.mongoskin.CoreServer.prototype.getServer)
- description and source-code
```javascript
getServer = function () {
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.insert"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>insert (ns, ops, options, callback)](#apidoc.element.mongoskin.CoreServer.prototype.insert)
- description and source-code
```javascript
insert = function (ns, ops, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {}, options = options || {};
  var result = basicWriteValidations(self, options);
  if(result) return callback(result);

  // If we are not connected or have a disconnectHandler specified
  if(disconnectHandler(self, 'insert', ns, ops, options, callback)) return;

  // Setup the docs as an array
  ops = Array.isArray(ops) ? ops : [ops];

  // Execute write
  return self.wireProtocolHandler.insert(self.s.pool, self.ismaster, ns, self.s.bson, ops, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.isConnected"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>isConnected ()](#apidoc.element.mongoskin.CoreServer.prototype.isConnected)
- description and source-code
```javascript
isConnected = function () {
  if(!this.s.pool) return false;
  return this.s.pool.isConnected();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.isDestroyed"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>isDestroyed ()](#apidoc.element.mongoskin.CoreServer.prototype.isDestroyed)
- description and source-code
```javascript
isDestroyed = function () {
  if(!this.s.pool) return false;
  return this.s.pool.isDestroyed();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.lastIsMaster"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>lastIsMaster ()](#apidoc.element.mongoskin.CoreServer.prototype.lastIsMaster)
- description and source-code
```javascript
lastIsMaster = function () {
  return this.ismaster;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.logout"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>logout (dbName, callback)](#apidoc.element.mongoskin.CoreServer.prototype.logout)
- description and source-code
```javascript
logout = function (dbName, callback) {
  this.s.pool.logout(dbName, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.remove"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>remove (ns, ops, options, callback)](#apidoc.element.mongoskin.CoreServer.prototype.remove)
- description and source-code
```javascript
remove = function (ns, ops, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {}, options = options || {};
  var result = basicWriteValidations(self, options);
  if(result) return callback(result);

  // If we are not connected or have a disconnectHandler specified
  if(disconnectHandler(self, 'remove', ns, ops, options, callback)) return;

  // Check if we have collation support
  if(this.ismaster && this.ismaster.maxWireVersion < 5 && options.collation) {
    return callback(new MongoError(f('server %s does not support collation', this.name)));
  }

  // Setup the docs as an array
  ops = Array.isArray(ops) ? ops : [ops];
  // Execute write
  return self.wireProtocolHandler.remove(self.s.pool, self.ismaster, ns, self.s.bson, ops, options, callback);
}
```
- example usage
```shell
...
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native

### Removed API from mongoskin 1.3.20
...
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.unref"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>unref ()](#apidoc.element.mongoskin.CoreServer.prototype.unref)
- description and source-code
```javascript
unref = function () {
  this.s.pool.unref();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.CoreServer.prototype.update"></a>[function <span class="apidocSignatureSpan">mongoskin.CoreServer.prototype.</span>update (ns, ops, options, callback)](#apidoc.element.mongoskin.CoreServer.prototype.update)
- description and source-code
```javascript
update = function (ns, ops, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {}, options = options || {};
  var result = basicWriteValidations(self, options);
  if(result) return callback(result);

  // If we are not connected or have a disconnectHandler specified
  if(disconnectHandler(self, 'update', ns, ops, options, callback)) return;

  // Check if we have collation support
  if(this.ismaster && this.ismaster.maxWireVersion < 5 && options.collation) {
    return callback(new MongoError(f('server %s does not support collation', this.name)));
  }

  // Setup the docs as an array
  ops = Array.isArray(ops) ? ops : [ops];
  // Execute write
  return self.wireProtocolHandler.update(self.s.pool, self.ismaster, ns, self.s.bson, ops, options, callback);
}
```
- example usage
```shell
...
### db.gridStore(...)
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native
...
```



# <a name="apidoc.module.mongoskin.Cursor"></a>[module mongoskin.Cursor](#apidoc.module.mongoskin.Cursor)

#### <a name="apidoc.element.mongoskin.Cursor.Cursor"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Cursor ()](#apidoc.element.mongoskin.Cursor.Cursor)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor._bindGetter"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.</span>_bindGetter (propName)](#apidoc.element.mongoskin.Cursor._bindGetter)
- description and source-code
```javascript
_bindGetter = function (propName) {
    SkinClass.prototype.__defineGetter__(propName, function() {
        return this._native && this._native[propName];// || this['_prop_' + propName];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor._bindMethod"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.</span>_bindMethod (propName)](#apidoc.element.mongoskin.Cursor._bindMethod)
- description and source-code
```javascript
_bindMethod = function (propName) {
  SkinClass.prototype[propName] = function() {
    var args = __slice.apply(arguments);
    if (this._state == STATE_OPEN) {
      this._native[propName].apply(this._native, args);
    } else {
      this.open(function(err, p_native) {
          if (err) {
            onError(err, args, skinClassName + '.' + propName);
          } else {
            p_native[propName].apply(p_native, args);
          }
      });
    }
    return this;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor._bindSetter"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.</span>_bindSetter (propName)](#apidoc.element.mongoskin.Cursor._bindSetter)
- description and source-code
```javascript
_bindSetter = function (propName) {
    SkinClass.prototype.__defineSetter__(propName, function(value) {
        // this['_prop_' + propName] = value;
        this.open(function(err, p_native) {
            if(err) return onError(err, args, skinClassName + '.' + propName);
            p_native[propName] = value;
        });
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Cursor.prototype"></a>[module mongoskin.Cursor.prototype](#apidoc.module.mongoskin.Cursor.prototype)

#### <a name="apidoc.element.mongoskin.Cursor.prototype._close"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>_close (callback)](#apidoc.element.mongoskin.Cursor.prototype._close)
- description and source-code
```javascript
_close = function (callback) {
  if(this._native.close) {
    this._native.close(callback)
  } else if(callback) {
    callback();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype._open"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>_open (callback)](#apidoc.element.mongoskin.Cursor.prototype._open)
- description and source-code
```javascript
_open = function (callback) {
  var self = this;
  this._skin_collection.open(function (err, collection) {
      if (err) return callback(err);
      var args = self._find_args.concat([callback]);
      collection.find.apply(collection, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.addCursorFlag"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>addCursorFlag ()](#apidoc.element.mongoskin.Cursor.prototype.addCursorFlag)
- description and source-code
```javascript
addCursorFlag = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.addListener"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>addListener ()](#apidoc.element.mongoskin.Cursor.prototype.addListener)
- description and source-code
```javascript
addListener = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.addQueryModifier"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>addQueryModifier ()](#apidoc.element.mongoskin.Cursor.prototype.addQueryModifier)
- description and source-code
```javascript
addQueryModifier = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.batchSize"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>batchSize ()](#apidoc.element.mongoskin.Cursor.prototype.batchSize)
- description and source-code
```javascript
batchSize = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.bufferedCount"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>bufferedCount ()](#apidoc.element.mongoskin.Cursor.prototype.bufferedCount)
- description and source-code
```javascript
bufferedCount = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.clone"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>clone ()](#apidoc.element.mongoskin.Cursor.prototype.clone)
- description and source-code
```javascript
clone = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>close (callback)](#apidoc.element.mongoskin.Cursor.prototype.close)
- description and source-code
```javascript
close = function (callback) {
  if (this._state === STATE_CLOSE) {
    callback && callback();
  } else if (this._state === STATE_OPEN) {
    this._state = STATE_CLOSE;
    this._close(callback);
  } else if (this._state === STATE_OPENNING) {
    var self = this;
    this._emitter.once('open', function (err, db) {
        self.close(callback);
    });
  }
  this._native = null;
  return this;
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.collation"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>collation ()](#apidoc.element.mongoskin.Cursor.prototype.collation)
- description and source-code
```javascript
collation = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.comment"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>comment ()](#apidoc.element.mongoskin.Cursor.prototype.comment)
- description and source-code
```javascript
comment = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.count"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>count ()](#apidoc.element.mongoskin.Cursor.prototype.count)
- description and source-code
```javascript
count = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.cursorBatchSize"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>cursorBatchSize ()](#apidoc.element.mongoskin.Cursor.prototype.cursorBatchSize)
- description and source-code
```javascript
cursorBatchSize = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.cursorLimit"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>cursorLimit ()](#apidoc.element.mongoskin.Cursor.prototype.cursorLimit)
- description and source-code
```javascript
cursorLimit = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.cursorSkip"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>cursorSkip ()](#apidoc.element.mongoskin.Cursor.prototype.cursorSkip)
- description and source-code
```javascript
cursorSkip = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.destroy"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>destroy ()](#apidoc.element.mongoskin.Cursor.prototype.destroy)
- description and source-code
```javascript
destroy = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.each"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>each ()](#apidoc.element.mongoskin.Cursor.prototype.each)
- description and source-code
```javascript
each = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
...
   cursor.toArray(fn);
 };
 this.find.apply(this, args);
 return this;
};

/**
* find and cursor.each(fn).
*
* @param {Object} [query]
* @param {Object} [options]
* @param {Function(err, item)} eachCallback
* @return {SkinCollection} this
* @api public
*/
...
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.emit"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>emit ()](#apidoc.element.mongoskin.Cursor.prototype.emit)
- description and source-code
```javascript
emit = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.eventNames"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>eventNames ()](#apidoc.element.mongoskin.Cursor.prototype.eventNames)
- description and source-code
```javascript
eventNames = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.explain"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>explain ()](#apidoc.element.mongoskin.Cursor.prototype.explain)
- description and source-code
```javascript
explain = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.filter"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>filter ()](#apidoc.element.mongoskin.Cursor.prototype.filter)
- description and source-code
```javascript
filter = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.forEach"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>forEach ()](#apidoc.element.mongoskin.Cursor.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.getMaxListeners"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>getMaxListeners ()](#apidoc.element.mongoskin.Cursor.prototype.getMaxListeners)
- description and source-code
```javascript
getMaxListeners = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.hasNext"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>hasNext ()](#apidoc.element.mongoskin.Cursor.prototype.hasNext)
- description and source-code
```javascript
hasNext = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.hint"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>hint ()](#apidoc.element.mongoskin.Cursor.prototype.hint)
- description and source-code
```javascript
hint = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.isClosed"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isClosed ()](#apidoc.element.mongoskin.Cursor.prototype.isClosed)
- description and source-code
```javascript
isClosed = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.isDead"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isDead ()](#apidoc.element.mongoskin.Cursor.prototype.isDead)
- description and source-code
```javascript
isDead = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.isKilled"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isKilled ()](#apidoc.element.mongoskin.Cursor.prototype.isKilled)
- description and source-code
```javascript
isKilled = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.isNotified"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isNotified ()](#apidoc.element.mongoskin.Cursor.prototype.isNotified)
- description and source-code
```javascript
isNotified = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.isOpen"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isOpen ()](#apidoc.element.mongoskin.Cursor.prototype.isOpen)
- description and source-code
```javascript
isOpen = function () {
  return this._state === STATE_OPEN;
}
```
- example usage
```shell
...
 * @param {Function(err, docs)} callback
 * @return {SkinCursor|SkinCollection} if last argument is not a function, then returns a SkinCursor,
 *   otherise return this
 * @api public
 */
SkinCollection.prototype.find = function (query, options, callback) {
var args = __slice.call(arguments);
if(this.isOpen()) {
  return this._native.find.apply(this._native, args);
}
if (args.length > 0 && typeof args[args.length - 1] === 'function') {
  this._find.apply(this, args);
  return this;
} else {
  var cursor = new SkinCursor();
...
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.isPaused"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>isPaused ()](#apidoc.element.mongoskin.Cursor.prototype.isPaused)
- description and source-code
```javascript
isPaused = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.kill"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>kill ()](#apidoc.element.mongoskin.Cursor.prototype.kill)
- description and source-code
```javascript
kill = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.limit"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>limit ()](#apidoc.element.mongoskin.Cursor.prototype.limit)
- description and source-code
```javascript
limit = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.listenerCount"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>listenerCount ()](#apidoc.element.mongoskin.Cursor.prototype.listenerCount)
- description and source-code
```javascript
listenerCount = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.listeners"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>listeners ()](#apidoc.element.mongoskin.Cursor.prototype.listeners)
- description and source-code
```javascript
listeners = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.map"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>map ()](#apidoc.element.mongoskin.Cursor.prototype.map)
- description and source-code
```javascript
map = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.max"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>max ()](#apidoc.element.mongoskin.Cursor.prototype.max)
- description and source-code
```javascript
max = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.maxAwaitTimeMS"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>maxAwaitTimeMS ()](#apidoc.element.mongoskin.Cursor.prototype.maxAwaitTimeMS)
- description and source-code
```javascript
maxAwaitTimeMS = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.maxScan"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>maxScan ()](#apidoc.element.mongoskin.Cursor.prototype.maxScan)
- description and source-code
```javascript
maxScan = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.maxTimeMS"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>maxTimeMS ()](#apidoc.element.mongoskin.Cursor.prototype.maxTimeMS)
- description and source-code
```javascript
maxTimeMS = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.maxTimeMs"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>maxTimeMs ()](#apidoc.element.mongoskin.Cursor.prototype.maxTimeMs)
- description and source-code
```javascript
maxTimeMs = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.min"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>min ()](#apidoc.element.mongoskin.Cursor.prototype.min)
- description and source-code
```javascript
min = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.next"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>next ()](#apidoc.element.mongoskin.Cursor.prototype.next)
- description and source-code
```javascript
next = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.nextObject"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>nextObject ()](#apidoc.element.mongoskin.Cursor.prototype.nextObject)
- description and source-code
```javascript
nextObject = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.on"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>on ()](#apidoc.element.mongoskin.Cursor.prototype.on)
- description and source-code
```javascript
on = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.once"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>once ()](#apidoc.element.mongoskin.Cursor.prototype.once)
- description and source-code
```javascript
once = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.open"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>open (callback)](#apidoc.element.mongoskin.Cursor.prototype.open)
- description and source-code
```javascript
open = function (callback) {
  switch (this._state) {
    case STATE_OPEN:
      callback(null, this._native);
      break;
    case STATE_OPENNING:
      this._emitter.once('open', callback);
      break;
    default:
      this._emitter.once('open', callback);
      this._state = STATE_OPENNING;
      var self = this;
      this._open(function(err, p_native) {
          if (err) {
            self._state = STATE_CLOSE;
          } else {
            self._state = STATE_OPEN;
            self._native = p_native;
          }
          self._emitter.emit('open', err, p_native);
      });
  }
  return this;
}
```
- example usage
```shell
...

alias origin 'db.collection(..., function(err, collection) {....})'

origin:

'''js
var db = new Db(...);
db.open(function(err, db) {
    db.collection('myCollection', {strict: true}, function(err, myCollection) {
        // myCollection.find() ...
    });
});
'''

mongoskin:
...
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.pause"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>pause ()](#apidoc.element.mongoskin.Cursor.prototype.pause)
- description and source-code
```javascript
pause = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.pipe"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>pipe ()](#apidoc.element.mongoskin.Cursor.prototype.pipe)
- description and source-code
```javascript
pipe = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.prependListener"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>prependListener ()](#apidoc.element.mongoskin.Cursor.prototype.prependListener)
- description and source-code
```javascript
prependListener = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.prependOnceListener"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>prependOnceListener ()](#apidoc.element.mongoskin.Cursor.prototype.prependOnceListener)
- description and source-code
```javascript
prependOnceListener = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.project"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>project ()](#apidoc.element.mongoskin.Cursor.prototype.project)
- description and source-code
```javascript
project = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.push"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>push ()](#apidoc.element.mongoskin.Cursor.prototype.push)
- description and source-code
```javascript
push = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.read"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>read ()](#apidoc.element.mongoskin.Cursor.prototype.read)
- description and source-code
```javascript
read = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.readBufferedDocuments"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>readBufferedDocuments ()](#apidoc.element.mongoskin.Cursor.prototype.readBufferedDocuments)
- description and source-code
```javascript
readBufferedDocuments = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.removeAllListeners"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>removeAllListeners ()](#apidoc.element.mongoskin.Cursor.prototype.removeAllListeners)
- description and source-code
```javascript
removeAllListeners = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.removeListener"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>removeListener ()](#apidoc.element.mongoskin.Cursor.prototype.removeListener)
- description and source-code
```javascript
removeListener = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.resume"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>resume ()](#apidoc.element.mongoskin.Cursor.prototype.resume)
- description and source-code
```javascript
resume = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.returnKey"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>returnKey ()](#apidoc.element.mongoskin.Cursor.prototype.returnKey)
- description and source-code
```javascript
returnKey = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.rewind"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>rewind ()](#apidoc.element.mongoskin.Cursor.prototype.rewind)
- description and source-code
```javascript
rewind = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.setCursorBatchSize"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setCursorBatchSize ()](#apidoc.element.mongoskin.Cursor.prototype.setCursorBatchSize)
- description and source-code
```javascript
setCursorBatchSize = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.setCursorLimit"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setCursorLimit ()](#apidoc.element.mongoskin.Cursor.prototype.setCursorLimit)
- description and source-code
```javascript
setCursorLimit = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.setCursorOption"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setCursorOption ()](#apidoc.element.mongoskin.Cursor.prototype.setCursorOption)
- description and source-code
```javascript
setCursorOption = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.setCursorSkip"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setCursorSkip ()](#apidoc.element.mongoskin.Cursor.prototype.setCursorSkip)
- description and source-code
```javascript
setCursorSkip = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.setEncoding"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setEncoding ()](#apidoc.element.mongoskin.Cursor.prototype.setEncoding)
- description and source-code
```javascript
setEncoding = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.setMaxListeners"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setMaxListeners ()](#apidoc.element.mongoskin.Cursor.prototype.setMaxListeners)
- description and source-code
```javascript
setMaxListeners = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.setReadPreference"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>setReadPreference ()](#apidoc.element.mongoskin.Cursor.prototype.setReadPreference)
- description and source-code
```javascript
setReadPreference = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
...
        new Server('localhost', 30000),
        new Server('localhost', 30001),
        new Server('localhost', 30002),
]);

var db = new Db('integration_test_', replSet, {w:0, native_parser: (process.env['TEST_NATIVE'] != null)});
// no need open and on('fullsetup', ...)
db.collection('myconnection').find().setReadPreference(ReadPreference.SECONDARY).toArray(function(err, items) {
        db.close();
});
'''

Model helper:

'''js
...
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.showRecordId"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>showRecordId ()](#apidoc.element.mongoskin.Cursor.prototype.showRecordId)
- description and source-code
```javascript
showRecordId = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.skip"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>skip ()](#apidoc.element.mongoskin.Cursor.prototype.skip)
- description and source-code
```javascript
skip = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.snapshot"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>snapshot ()](#apidoc.element.mongoskin.Cursor.prototype.snapshot)
- description and source-code
```javascript
snapshot = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.sort"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>sort ()](#apidoc.element.mongoskin.Cursor.prototype.sort)
- description and source-code
```javascript
sort = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.stream"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>stream ()](#apidoc.element.mongoskin.Cursor.prototype.stream)
- description and source-code
```javascript
stream = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.toArray"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>toArray ()](#apidoc.element.mongoskin.Cursor.prototype.toArray)
- description and source-code
```javascript
toArray = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
...

Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
...
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.unpipe"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>unpipe ()](#apidoc.element.mongoskin.Cursor.prototype.unpipe)
- description and source-code
```javascript
unpipe = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.unshift"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>unshift ()](#apidoc.element.mongoskin.Cursor.prototype.unshift)
- description and source-code
```javascript
unshift = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
...
SkinDb.prototype.admin = function () {
  return new SkinAdmin(this);
}

SkinDb.prototype.gridStore = function () {
  var skinGridStore = new SkinGridStore();
  var args = Array.prototype.slice.call(arguments);
  args.unshift(this);
  skinGridStore._construct_args = args;
  return skinGridStore;
}
...
```

#### <a name="apidoc.element.mongoskin.Cursor.prototype.wrap"></a>[function <span class="apidocSignatureSpan">mongoskin.Cursor.prototype.</span>wrap ()](#apidoc.element.mongoskin.Cursor.prototype.wrap)
- description and source-code
```javascript
wrap = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.DBRef"></a>[module mongoskin.DBRef](#apidoc.module.mongoskin.DBRef)

#### <a name="apidoc.element.mongoskin.DBRef.DBRef"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>DBRef (namespace, oid, db)](#apidoc.element.mongoskin.DBRef.DBRef)
- description and source-code
```javascript
function DBRef(namespace, oid, db) {
  if(!(this instanceof DBRef)) return new DBRef(namespace, oid, db);

  this._bsontype = 'DBRef';
  this.namespace = namespace;
  this.oid = oid;
  this.db = db;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.DBRef.prototype"></a>[module mongoskin.DBRef.prototype](#apidoc.module.mongoskin.DBRef.prototype)

#### <a name="apidoc.element.mongoskin.DBRef.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.DBRef.prototype.</span>toJSON ()](#apidoc.element.mongoskin.DBRef.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return {
    '$ref':this.namespace,
    '$id':this.oid,
    '$db':this.db == null ? '' : this.db
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Db"></a>[module mongoskin.Db](#apidoc.module.mongoskin.Db)

#### <a name="apidoc.element.mongoskin.Db.Db"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Db ()](#apidoc.element.mongoskin.Db.Db)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db._bindGetter"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.</span>_bindGetter (propName)](#apidoc.element.mongoskin.Db._bindGetter)
- description and source-code
```javascript
_bindGetter = function (propName) {
    SkinClass.prototype.__defineGetter__(propName, function() {
        return this._native && this._native[propName];// || this['_prop_' + propName];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db._bindMethod"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.</span>_bindMethod (propName)](#apidoc.element.mongoskin.Db._bindMethod)
- description and source-code
```javascript
_bindMethod = function (propName) {
  SkinClass.prototype[propName] = function() {
    var args = __slice.apply(arguments);
    if (this._state == STATE_OPEN) {
      this._native[propName].apply(this._native, args);
    } else {
      this.open(function(err, p_native) {
          if (err) {
            onError(err, args, skinClassName + '.' + propName);
          } else {
            p_native[propName].apply(p_native, args);
          }
      });
    }
    return this;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db._bindSetter"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.</span>_bindSetter (propName)](#apidoc.element.mongoskin.Db._bindSetter)
- description and source-code
```javascript
_bindSetter = function (propName) {
    SkinClass.prototype.__defineSetter__(propName, function(value) {
        // this['_prop_' + propName] = value;
        this.open(function(err, p_native) {
            if(err) return onError(err, args, skinClassName + '.' + propName);
            p_native[propName] = value;
        });
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Db.prototype"></a>[module mongoskin.Db.prototype](#apidoc.module.mongoskin.Db.prototype)

#### <a name="apidoc.element.mongoskin.Db.prototype._admin"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>_admin ()](#apidoc.element.mongoskin.Db.prototype._admin)
- description and source-code
```javascript
_admin = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype._close"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>_close (callback)](#apidoc.element.mongoskin.Db.prototype._close)
- description and source-code
```javascript
_close = function (callback) {
  if(this._native.close) {
    this._native.close(callback)
  } else if(callback) {
    callback();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype._open"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>_open (callback)](#apidoc.element.mongoskin.Db.prototype._open)
- description and source-code
```javascript
_open = function (callback) {
  // TODO authenticate support
  if(this._native) {
    this._native.open(callback);
  } else if(this._connect_args) {
    var args = this._connect_args.concat(callback);
    MongoClient.connect.apply(MongoClient, args);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.addChild"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>addChild ()](#apidoc.element.mongoskin.Db.prototype.addChild)
- description and source-code
```javascript
addChild = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.addListener"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>addListener ()](#apidoc.element.mongoskin.Db.prototype.addListener)
- description and source-code
```javascript
addListener = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.addUser"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>addUser ()](#apidoc.element.mongoskin.Db.prototype.addUser)
- description and source-code
```javascript
addUser = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.admin"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>admin ()](#apidoc.element.mongoskin.Db.prototype.admin)
- description and source-code
```javascript
admin = function () {
  return new SkinAdmin(this);
}
```
- example usage
```shell
...
'''js
db.bind('article')
db.article.find().toArray(function(err, items) {
  assert.ok(err == null);
});
'''

### db.admin(...)
alias 'new Admin(db, ...)'
### db.grid(...)
alias 'new Grid(db, ...)'
### db.gridStore(...)
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
...
```

#### <a name="apidoc.element.mongoskin.Db.prototype.authenticate"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>authenticate ()](#apidoc.element.mongoskin.Db.prototype.authenticate)
- description and source-code
```javascript
authenticate = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.bind"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>bind (name, options)](#apidoc.element.mongoskin.Db.prototype.bind)
- description and source-code
```javascript
bind = function (name, options) {
  return this[name] = this.collection(name, options);
}
```
- example usage
```shell
...
========

Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet
...
```

#### <a name="apidoc.element.mongoskin.Db.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>close (callback)](#apidoc.element.mongoskin.Db.prototype.close)
- description and source-code
```javascript
close = function (callback) {
  if (this._state === STATE_CLOSE) {
    callback && callback();
  } else if (this._state === STATE_OPEN) {
    this._state = STATE_CLOSE;
    this._close(callback);
  } else if (this._state === STATE_OPENNING) {
    var self = this;
    this._emitter.once('open', function (err, db) {
        self.close(callback);
    });
  }
  this._native = null;
  return this;
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.Db.prototype.collection"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>collection (name, options)](#apidoc.element.mongoskin.Db.prototype.collection)
- description and source-code
```javascript
collection = function (name, options) {
  // Ooops, no extended mthods like findById etc.
  // if(this.isOpen() && (!options || !options.strict) && !callback) {
  //   // mongodb now support collection without callback
  //   // see: http://mongodb.github.io/node-mongodb-native/api-generated/db.html#collection
  //   return this._native.collection(name, options);
  // }
  var collection = new SkinCollection();
  collection._skin_db = this;
  collection._collection_args = [name, options];
  return collection;
}
```
- example usage
```shell
...
        new Server('localhost', 30000),
        new Server('localhost', 30001),
        new Server('localhost', 30002),
]);

var db = new Db('integration_test_', replSet, {w:0, native_parser: (process.env['TEST_NATIVE'] != null)});
// no need open and on('fullsetup', ...)
db.collection('myconnection').find().setReadPreference(ReadPreference.SECONDARY).toArray(function(err, items) {
        db.close();
});
'''

Model helper:

'''js
...
```

#### <a name="apidoc.element.mongoskin.Db.prototype.collections"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>collections ()](#apidoc.element.mongoskin.Db.prototype.collections)
- description and source-code
```javascript
collections = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.command"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>command ()](#apidoc.element.mongoskin.Db.prototype.command)
- description and source-code
```javascript
command = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.createCollection"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>createCollection ()](#apidoc.element.mongoskin.Db.prototype.createCollection)
- description and source-code
```javascript
createCollection = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.createIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>createIndex ()](#apidoc.element.mongoskin.Db.prototype.createIndex)
- description and source-code
```javascript
createIndex = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.db"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>db ()](#apidoc.element.mongoskin.Db.prototype.db)
- description and source-code
```javascript
db = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
...
Usage
========

Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet
...
```

#### <a name="apidoc.element.mongoskin.Db.prototype.dropCollection"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>dropCollection ()](#apidoc.element.mongoskin.Db.prototype.dropCollection)
- description and source-code
```javascript
dropCollection = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.dropDatabase"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>dropDatabase ()](#apidoc.element.mongoskin.Db.prototype.dropDatabase)
- description and source-code
```javascript
dropDatabase = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.emit"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>emit ()](#apidoc.element.mongoskin.Db.prototype.emit)
- description and source-code
```javascript
emit = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.ensureIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>ensureIndex ()](#apidoc.element.mongoskin.Db.prototype.ensureIndex)
- description and source-code
```javascript
ensureIndex = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.eval"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>eval ()](#apidoc.element.mongoskin.Db.prototype.eval)
- description and source-code
```javascript
eval = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.eventNames"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>eventNames ()](#apidoc.element.mongoskin.Db.prototype.eventNames)
- description and source-code
```javascript
eventNames = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.executeDbAdminCommand"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>executeDbAdminCommand ()](#apidoc.element.mongoskin.Db.prototype.executeDbAdminCommand)
- description and source-code
```javascript
executeDbAdminCommand = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.getMaxListeners"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>getMaxListeners ()](#apidoc.element.mongoskin.Db.prototype.getMaxListeners)
- description and source-code
```javascript
getMaxListeners = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.gridStore"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>gridStore ()](#apidoc.element.mongoskin.Db.prototype.gridStore)
- description and source-code
```javascript
gridStore = function () {
  var skinGridStore = new SkinGridStore();
  var args = Array.prototype.slice.call(arguments);
  args.unshift(this);
  skinGridStore._construct_args = args;
  return skinGridStore;
}
```
- example usage
```shell
...
});
'''

### db.admin(...)
alias 'new Admin(db, ...)'
### db.grid(...)
alias 'new Grid(db, ...)'
### db.gridStore(...)
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
...
```

#### <a name="apidoc.element.mongoskin.Db.prototype.indexInformation"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>indexInformation ()](#apidoc.element.mongoskin.Db.prototype.indexInformation)
- description and source-code
```javascript
indexInformation = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.isOpen"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>isOpen ()](#apidoc.element.mongoskin.Db.prototype.isOpen)
- description and source-code
```javascript
isOpen = function () {
  return this._state === STATE_OPEN;
}
```
- example usage
```shell
...
 * @param {Function(err, docs)} callback
 * @return {SkinCursor|SkinCollection} if last argument is not a function, then returns a SkinCursor,
 *   otherise return this
 * @api public
 */
SkinCollection.prototype.find = function (query, options, callback) {
var args = __slice.call(arguments);
if(this.isOpen()) {
  return this._native.find.apply(this._native, args);
}
if (args.length > 0 && typeof args[args.length - 1] === 'function') {
  this._find.apply(this, args);
  return this;
} else {
  var cursor = new SkinCursor();
...
```

#### <a name="apidoc.element.mongoskin.Db.prototype.listCollections"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>listCollections ()](#apidoc.element.mongoskin.Db.prototype.listCollections)
- description and source-code
```javascript
listCollections = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.listenerCount"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>listenerCount ()](#apidoc.element.mongoskin.Db.prototype.listenerCount)
- description and source-code
```javascript
listenerCount = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.listeners"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>listeners ()](#apidoc.element.mongoskin.Db.prototype.listeners)
- description and source-code
```javascript
listeners = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.logout"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>logout ()](#apidoc.element.mongoskin.Db.prototype.logout)
- description and source-code
```javascript
logout = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.on"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>on ()](#apidoc.element.mongoskin.Db.prototype.on)
- description and source-code
```javascript
on = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.once"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>once ()](#apidoc.element.mongoskin.Db.prototype.once)
- description and source-code
```javascript
once = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.open"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>open (callback)](#apidoc.element.mongoskin.Db.prototype.open)
- description and source-code
```javascript
open = function (callback) {
  switch (this._state) {
    case STATE_OPEN:
      callback(null, this._native);
      break;
    case STATE_OPENNING:
      this._emitter.once('open', callback);
      break;
    default:
      this._emitter.once('open', callback);
      this._state = STATE_OPENNING;
      var self = this;
      this._open(function(err, p_native) {
          if (err) {
            self._state = STATE_CLOSE;
          } else {
            self._state = STATE_OPEN;
            self._native = p_native;
          }
          self._emitter.emit('open', err, p_native);
      });
  }
  return this;
}
```
- example usage
```shell
...

alias origin 'db.collection(..., function(err, collection) {....})'

origin:

'''js
var db = new Db(...);
db.open(function(err, db) {
    db.collection('myCollection', {strict: true}, function(err, myCollection) {
        // myCollection.find() ...
    });
});
'''

mongoskin:
...
```

#### <a name="apidoc.element.mongoskin.Db.prototype.prependListener"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>prependListener ()](#apidoc.element.mongoskin.Db.prototype.prependListener)
- description and source-code
```javascript
prependListener = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.prependOnceListener"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>prependOnceListener ()](#apidoc.element.mongoskin.Db.prototype.prependOnceListener)
- description and source-code
```javascript
prependOnceListener = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.removeAllListeners"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>removeAllListeners ()](#apidoc.element.mongoskin.Db.prototype.removeAllListeners)
- description and source-code
```javascript
removeAllListeners = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.removeListener"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>removeListener ()](#apidoc.element.mongoskin.Db.prototype.removeListener)
- description and source-code
```javascript
removeListener = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.removeUser"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>removeUser ()](#apidoc.element.mongoskin.Db.prototype.removeUser)
- description and source-code
```javascript
removeUser = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.renameCollection"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>renameCollection ()](#apidoc.element.mongoskin.Db.prototype.renameCollection)
- description and source-code
```javascript
renameCollection = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.setMaxListeners"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>setMaxListeners ()](#apidoc.element.mongoskin.Db.prototype.setMaxListeners)
- description and source-code
```javascript
setMaxListeners = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.stats"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>stats ()](#apidoc.element.mongoskin.Db.prototype.stats)
- description and source-code
```javascript
stats = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Db.prototype.unref"></a>[function <span class="apidocSignatureSpan">mongoskin.Db.prototype.</span>unref ()](#apidoc.element.mongoskin.Db.prototype.unref)
- description and source-code
```javascript
unref = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Decimal128"></a>[module mongoskin.Decimal128](#apidoc.module.mongoskin.Decimal128)

#### <a name="apidoc.element.mongoskin.Decimal128.Decimal128"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Decimal128 (bytes)](#apidoc.element.mongoskin.Decimal128.Decimal128)
- description and source-code
```javascript
Decimal128 = function (bytes) {
  this._bsontype = 'Decimal128';
  this.bytes = bytes;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Decimal128.fromString"></a>[function <span class="apidocSignatureSpan">mongoskin.Decimal128.</span>fromString (string)](#apidoc.element.mongoskin.Decimal128.fromString)
- description and source-code
```javascript
fromString = function (string) {
  // Parse state tracking
  var isNegative = false;
  var sawRadix = false;
  var foundNonZero = false;

  // Total number of significant digits (no leading or trailing zero)
  var significantDigits = 0;
  // Total number of significand digits read
  var nDigitsRead = 0;
  // Total number of digits (no leading zeros)
  var nDigits = 0;
  // The number of the digits after radix
  var radixPosition = 0;
  // The index of the first non-zero in *str*
  var firstNonZero = 0;

  // Digits Array
  var digits = [0];
  // The number of digits in digits
  var nDigitsStored = 0;
  // Insertion pointer for digits
  var digitsInsert = 0;
  // The index of the first non-zero digit
  var firstDigit = 0;
  // The index of the last digit
  var lastDigit = 0;

  // Exponent
  var exponent = 0;
  // loop index over array
  var i = 0;
  // The high 17 digits of the significand
  var significandHigh = [0, 0];
  // The low 17 digits of the significand
  var significandLow = [0, 0];
  // The biased exponent
  var biasedExponent = 0;

  // Read index
  var index = 0;

  // Trim the string
  string = string.trim();

  // Results
  var stringMatch = string.match(PARSE_STRING_REGEXP);
  var infMatch = string.match(PARSE_INF_REGEXP);
  var nanMatch = string.match(PARSE_NAN_REGEXP);

  // Validate the string
  if(!stringMatch
    && ! infMatch
    && ! nanMatch || string.length == 0) {
      throw new Error("" + string + " not a valid Decimal128 string");
  }

  // Check if we have an illegal exponent format
  if(stringMatch && stringMatch[4] && stringMatch[2] === undefined) {
    throw new Error("" + string + " not a valid Decimal128 string");
  }

  // Get the negative or positive sign
  if(string[index] == '+' || string[index] == '-') {
    isNegative = string[index++] == '-';
  }

  // Check if user passed Infinity or NaN
  if(!isDigit(string[index]) && string[index] != '.') {
    if(string[index] == 'i' || string[index] == 'I') {
      return new Decimal128(new Buffer(isNegative ? INF_NEGATIVE_BUFFER : INF_POSITIVE_BUFFER));
    } else if(string[index] == 'N') {
      return new Decimal128(new Buffer(NAN_BUFFER));
    }
  }

  // Read all the digits
  while(isDigit(string[index]) || string[index] == '.') {
    if(string[index] == '.') {
      if(sawRadix) {
        return new Decimal128(new Buffer(NAN_BUFFER));
      }

      sawRadix = true;
      index = index + 1;
      continue;
    }

    if(nDigitsStored < 34) {
      if(string[index] != '0' || foundNonZero) {
        if(!foundNonZero) {
          firstNonZero = nDigitsRead;
        }

        foundNonZero = true;

        // Only store 34 digits
        digits[digitsInsert++] = parseInt(string[index], 10);
        nDigitsStored = nDigitsStored + 1;
      }
    }

    if(foundNonZero) {
      nDigits = nDigits + 1;
    }

    if(sawRadix) {
      radixPosition = radixPosition + 1;
    }

    nDigitsRead = nDigitsRead + 1;
    index = index + 1;
  }

  if(sawRadix && !nDigitsRead) {
    throw new Error("" + string + " not a valid Decimal128 string");
  }

  // Read exponent if exists
  if(string[index] == 'e' || string[index] == 'E') {
    // Read exponent digits
    var match = string.substr(++index).match(EXPONENT_REGEX);

    // No digits read
    if(!match || !match[2]) {
      return new Decimal128(new Buffer(NAN_BUFFER));
    }

    // Get exponent
    exponent = parseInt(match[0], 10);

    // Adjust the index
    index = index + match[0].length;
  }

  // Return not a number
  if(string[index]) {
    return new Decimal128(new Buffer(NAN_BUFFER));
  }

  // Done reading input
  // Find first non-zero digit in digits
  firstDigit = 0;

  if(!nDigitsStored) {
    firstDigit = 0;
    lastDigit = 0;
    digits[0] = 0;
    nDigits = 1;
    nDigitsStored = 1;
    significantDigits = 0;
  } else {
    lastDigit = nDigitsStored - 1;
    significantDigits = nDigits;

    if(exponent != 0 && significantDigits != 1) {
      while(string[firstNonZero + significantDigits - 1] == '0') {
        significantDigits = significantDigits - 1;
      }
    }
  }

  // Normalization of ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Decimal128.prototype"></a>[module mongoskin.Decimal128.prototype](#apidoc.module.mongoskin.Decimal128.prototype)

#### <a name="apidoc.element.mongoskin.Decimal128.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.Decimal128.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Decimal128.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return { "$numberDecimal": this.toString() };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Decimal128.prototype.toString"></a>[function <span class="apidocSignatureSpan">mongoskin.Decimal128.prototype.</span>toString ()](#apidoc.element.mongoskin.Decimal128.prototype.toString)
- description and source-code
```javascript
toString = function () {
  // Note: bits in this routine are referred to starting at 0,
  // from the sign bit, towards the coefficient.

  // bits 0 - 31
  var high;
  // bits 32 - 63
  var midh;
  // bits 64 - 95
  var midl;
  // bits 96 - 127
  var low;
  // bits 1 - 5
  var combination;
  // decoded biased exponent (14 bits)
  var biased_exponent;
  // the number of significand digits
  var significand_digits = 0;
  // the base-10 digits in the significand
  var significand = new Array(36);
  for(var i = 0; i < significand.length; i++) significand[i] = 0;
  // read pointer into significand
  var index = 0;

  // unbiased exponent
  var exponent;
  // the exponent if scientific notation is used
  var scientific_exponent;

  // true if the number is zero
  var is_zero = false;

  // the most signifcant significand bits (50-46)
  var significand_msb;
  // temporary storage for significand decoding
  var significand128 = {parts: new Array(4)};
  // indexing variables
  var i;
  var j, k;

  // Output string
  var string = [];

  // Unpack index
  var index = 0;

  // Buffer reference
  var buffer = this.bytes;

  // Unpack the low 64bits into a long
  low = buffer[index++] | buffer[index++] << 8 | buffer[index++] << 16 | buffer[index++] << 24;
  midl = buffer[index++] | buffer[index++] << 8 | buffer[index++] << 16 | buffer[index++] << 24;

  // Unpack the high 64bits into a long
  midh = buffer[index++] | buffer[index++] << 8 | buffer[index++] << 16 | buffer[index++] << 24;
  high = buffer[index++] | buffer[index++] << 8 | buffer[index++] << 16 | buffer[index++] << 24;

  // Unpack index
  var index = 0;

  // Create the state of the decimal
  var dec = {
    low: new Long(low, midl),
    high: new Long(midh, high) };

  if(dec.high.lessThan(Long.ZERO)) {
    string.push('-');
  }

  // Decode combination field and exponent
  combination = (high >> 26) & COMBINATION_MASK;

  if((combination >> 3) == 3) {
    // Check for 'special' values
    if(combination == COMBINATION_INFINITY) {
      return string.join('') + "Infinity";
    } else if(combination == COMBINATION_NAN) {
      return "NaN";
    } else {
      biased_exponent = (high >> 15) & EXPONENT_MASK;
      significand_msb = 0x08 + ((high >> 14) & 0x01);
    }
  } else {
    significand_msb = (high >> 14) & 0x07;
    biased_exponent = (high >> 17) & EXPONENT_MASK;
  }

  exponent = biased_exponent - EXPONENT_BIAS;

  // Create string of significand digits

  // Convert the 114-bit binary number represented by
  // (significand_high, significand_low) to at most 34 decimal
  // digits through modulo and division.
  significand128.parts[0] = (high & 0x3fff) + ((significand_msb & 0xf) << 14);
  significand128.parts[1] = midh;
  significand128.parts[2] = midl;
  significand128.parts[3] = low;

  if(significand128.parts[0] == 0 && significand128.parts[1] == 0
    && significand128.parts[2] == 0 && significand128.parts[3] == 0) {
      is_zero = true;
  } else {
    for(var k = 3; k >= 0; k--) {
      var least_digits = 0;
      // Peform the divide
      var result = divideu128(significand128);
      significand128 = result.quotient;
      least_digits = result.rem.low_;

      // We now have the 9 least significant digits (in base 2).
      // Convert and output to string.
      if(!least_digits) continue;

      for(var j = 8; j >= 0; j--) {
        // significand[k * 9 + j] = Math.round(least_digits % 10);
        significand[k * 9 + j] = least_digits % 10;
        // least_digits = Math.round(least_digits / 10);
        least_digits = Math.floor(least_digits / 10);
      }
    }
  }

  // Output format options:
  // Scientific - [-]d.dddE(+/-)dd or [-]dE(+/-)dd
  // Regular    - ddd.ddd

  if(is_zero) {
    significand_digits = 1;
    significand[index] = 0;
  } else {
    significand_digits = 36;
    var i = 0;

    while(!significand[index]) {
      i++;
      significand_digits = significand_digits - 1;
      index = index + 1;
    }
  }

  scientific_exponent = significand_digits - 1 + exponent;

  // The scientific exponent checks are dictated by the string conversion
  // ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Double"></a>[module mongoskin.Double](#apidoc.module.mongoskin.Double)

#### <a name="apidoc.element.mongoskin.Double.Double"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Double (value)](#apidoc.element.mongoskin.Double.Double)
- description and source-code
```javascript
function Double(value) {
  if(!(this instanceof Double)) return new Double(value);

  this._bsontype = 'Double';
  this.value = value;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Double.prototype"></a>[module mongoskin.Double.prototype](#apidoc.module.mongoskin.Double.prototype)

#### <a name="apidoc.element.mongoskin.Double.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.Double.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Double.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Double.prototype.valueOf"></a>[function <span class="apidocSignatureSpan">mongoskin.Double.prototype.</span>valueOf ()](#apidoc.element.mongoskin.Double.prototype.valueOf)
- description and source-code
```javascript
valueOf = function () {
  return this.value;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.GridFSBucket"></a>[module mongoskin.GridFSBucket](#apidoc.module.mongoskin.GridFSBucket)

#### <a name="apidoc.element.mongoskin.GridFSBucket.GridFSBucket"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>GridFSBucket (db, options)](#apidoc.element.mongoskin.GridFSBucket.GridFSBucket)
- description and source-code
```javascript
function GridFSBucket(db, options) {
  Emitter.apply(this);
  this.setMaxListeners(0);

  if (options && typeof options === 'object') {
    options = shallowClone(options);
    var keys = Object.keys(DEFAULT_GRIDFS_BUCKET_OPTIONS);
    for (var i = 0; i < keys.length; ++i) {
      if (!options[keys[i]]) {
        options[keys[i]] = DEFAULT_GRIDFS_BUCKET_OPTIONS[keys[i]];
      }
    }
  } else {
    options = DEFAULT_GRIDFS_BUCKET_OPTIONS;
  }

  this.s = {
    db: db,
    options: options,
    _chunksCollection: db.collection(options.bucketName + '.chunks'),
    _filesCollection: db.collection(options.bucketName + '.files'),
    checkedIndexes: false,
    calledOpenUploadStream: false,
    promiseLibrary: db.s.promiseLibrary ||
      (typeof global.Promise == 'function' ? global.Promise : require('es6-promise').Promise)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridFSBucket.super_"></a>[function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.</span>super_ ()](#apidoc.element.mongoskin.GridFSBucket.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.GridFSBucket.prototype"></a>[module mongoskin.GridFSBucket.prototype](#apidoc.module.mongoskin.GridFSBucket.prototype)

#### <a name="apidoc.element.mongoskin.GridFSBucket.prototype.delete"></a>[function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>delete (id, callback)](#apidoc.element.mongoskin.GridFSBucket.prototype.delete)
- description and source-code
```javascript
delete = function (id, callback) {
  if (typeof callback === 'function') {
    return _delete(this, id, callback);
  }

  var _this = this;
  return new this.s.promiseLibrary(function(resolve, reject) {
    _delete(_this, id, function(error, res) {
      if (error) {
        reject(error);
      } else {
        resolve(res);
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridFSBucket.prototype.drop"></a>[function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>drop (callback)](#apidoc.element.mongoskin.GridFSBucket.prototype.drop)
- description and source-code
```javascript
drop = function (callback) {
  if (typeof callback === 'function') {
    return _drop(this, callback);
  }

  var _this = this;
  return new this.s.promiseLibrary(function(resolve, reject) {
    _drop(_this, function(error, res) {
      if (error) {
        reject(error);
      } else {
        resolve(res);
      }
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridFSBucket.prototype.find"></a>[function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>find (filter, options)](#apidoc.element.mongoskin.GridFSBucket.prototype.find)
- description and source-code
```javascript
find = function (filter, options) {
  filter = filter || {};
  options = options || {};

  var cursor = this.s._filesCollection.find(filter);

  if (options.batchSize != null) {
    cursor.batchSize(options.batchSize);
  }
  if (options.limit != null) {
    cursor.limit(options.limit);
  }
  if (options.maxTimeMS != null) {
    cursor.maxTimeMS(options.maxTimeMS);
  }
  if (options.noCursorTimeout != null) {
    cursor.addCursorFlag('noCursorTimeout', options.noCursorTimeout);
  }
  if (options.skip != null) {
    cursor.skip(options.skip);
  }
  if (options.sort != null) {
    cursor.sort(options.sort);
  }

  return cursor;
}
```
- example usage
```shell
...

Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
...
```

#### <a name="apidoc.element.mongoskin.GridFSBucket.prototype.openDownloadStream"></a>[function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>openDownloadStream (id, options)](#apidoc.element.mongoskin.GridFSBucket.prototype.openDownloadStream)
- description and source-code
```javascript
openDownloadStream = function (id, options) {
  var filter = { _id: id };
  options = {
    start: options && options.start,
    end: options && options.end
  };

  return new GridFSBucketReadStream(this.s._chunksCollection,
    this.s._filesCollection, this.s.options.readPreference, filter, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridFSBucket.prototype.openDownloadStreamByName"></a>[function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>openDownloadStreamByName (filename, options)](#apidoc.element.mongoskin.GridFSBucket.prototype.openDownloadStreamByName)
- description and source-code
```javascript
openDownloadStreamByName = function (filename, options) {
  var sort = { uploadDate: -1 };
  var skip = null;
  if (options && options.revision != null) {
    if (options.revision >= 0) {
      sort = { uploadDate: 1 };
      skip = options.revision;
    } else {
      skip = -options.revision - 1;
    }
  }

  var filter = { filename: filename };
  options = {
    sort: sort,
    skip: skip,
    start: options && options.start,
    end: options && options.end
  };
  return new GridFSBucketReadStream(this.s._chunksCollection,
    this.s._filesCollection, this.s.options.readPreference, filter, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridFSBucket.prototype.openUploadStream"></a>[function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>openUploadStream (filename, options)](#apidoc.element.mongoskin.GridFSBucket.prototype.openUploadStream)
- description and source-code
```javascript
openUploadStream = function (filename, options) {
  if (options) {
    options = shallowClone(options);
  } else {
    options = {};
  }
  if (!options.chunkSizeBytes) {
    options.chunkSizeBytes = this.s.options.chunkSizeBytes;
  }
  return new GridFSBucketWriteStream(this, filename, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridFSBucket.prototype.openUploadStreamWithId"></a>[function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>openUploadStreamWithId (id, filename, options)](#apidoc.element.mongoskin.GridFSBucket.prototype.openUploadStreamWithId)
- description and source-code
```javascript
openUploadStreamWithId = function (id, filename, options) {
  if (options) {
    options = shallowClone(options);
  } else {
    options = {};
  }

  if (!options.chunkSizeBytes) {
    options.chunkSizeBytes = this.s.options.chunkSizeBytes;
  }

  options.id = id;

  return new GridFSBucketWriteStream(this, filename, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridFSBucket.prototype.rename"></a>[function <span class="apidocSignatureSpan">mongoskin.GridFSBucket.prototype.</span>rename (id, filename, callback)](#apidoc.element.mongoskin.GridFSBucket.prototype.rename)
- description and source-code
```javascript
rename = function (id, filename, callback) {
  if (typeof callback === 'function') {
    return _rename(this, id, filename, callback);
  }

  var _this = this;
  return new this.s.promiseLibrary(function(resolve, reject) {
    _rename(_this, id, filename, function(error, res) {
      if (error) {
        reject(error);
      } else {
        resolve(res);
      }
    });
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.GridStore"></a>[module mongoskin.GridStore](#apidoc.module.mongoskin.GridStore)

#### <a name="apidoc.element.mongoskin.GridStore.GridStore"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>GridStore ()](#apidoc.element.mongoskin.GridStore.GridStore)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore._bindGetter"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>_bindGetter (propName)](#apidoc.element.mongoskin.GridStore._bindGetter)
- description and source-code
```javascript
_bindGetter = function (propName) {
    SkinClass.prototype.__defineGetter__(propName, function() {
        return this._native && this._native[propName];// || this['_prop_' + propName];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore._bindMethod"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>_bindMethod (propName)](#apidoc.element.mongoskin.GridStore._bindMethod)
- description and source-code
```javascript
_bindMethod = function (propName) {
  SkinClass.prototype[propName] = function() {
    var args = __slice.apply(arguments);
    if (this._state == STATE_OPEN) {
      this._native[propName].apply(this._native, args);
    } else {
      this.open(function(err, p_native) {
          if (err) {
            onError(err, args, skinClassName + '.' + propName);
          } else {
            p_native[propName].apply(p_native, args);
          }
      });
    }
    return this;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore._bindSetter"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>_bindSetter (propName)](#apidoc.element.mongoskin.GridStore._bindSetter)
- description and source-code
```javascript
_bindSetter = function (propName) {
    SkinClass.prototype.__defineSetter__(propName, function(value) {
        // this['_prop_' + propName] = value;
        this.open(function(err, p_native) {
            if(err) return onError(err, args, skinClassName + '.' + propName);
            p_native[propName] = value;
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.exist"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>exist (skindb)](#apidoc.element.mongoskin.GridStore.exist)
- description and source-code
```javascript
exist = function (skindb) {
  var args = Array.prototype.slice.call(arguments);
  skindb.open(function(err, p_db) {
      args[0] = p_db;
      GridStore[methodName].apply(GridStore, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.list"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>list (skindb)](#apidoc.element.mongoskin.GridStore.list)
- description and source-code
```javascript
list = function (skindb) {
  var args = Array.prototype.slice.call(arguments);
  skindb.open(function(err, p_db) {
      args[0] = p_db;
      GridStore[methodName].apply(GridStore, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.read"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>read (skindb)](#apidoc.element.mongoskin.GridStore.read)
- description and source-code
```javascript
read = function (skindb) {
  var args = Array.prototype.slice.call(arguments);
  skindb.open(function(err, p_db) {
      args[0] = p_db;
      GridStore[methodName].apply(GridStore, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.readlines"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>readlines (skindb)](#apidoc.element.mongoskin.GridStore.readlines)
- description and source-code
```javascript
readlines = function (skindb) {
  var args = Array.prototype.slice.call(arguments);
  skindb.open(function(err, p_db) {
      args[0] = p_db;
      GridStore[methodName].apply(GridStore, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.unlink"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.</span>unlink (skindb)](#apidoc.element.mongoskin.GridStore.unlink)
- description and source-code
```javascript
unlink = function (skindb) {
  var args = Array.prototype.slice.call(arguments);
  skindb.open(function(err, p_db) {
      args[0] = p_db;
      GridStore[methodName].apply(GridStore, args);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.GridStore.prototype"></a>[module mongoskin.GridStore.prototype](#apidoc.module.mongoskin.GridStore.prototype)

#### <a name="apidoc.element.mongoskin.GridStore.prototype._close"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>_close (callback)](#apidoc.element.mongoskin.GridStore.prototype._close)
- description and source-code
```javascript
_close = function (callback) {
  if(this._native.close) {
    this._native.close(callback)
  } else if(callback) {
    callback();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype._open"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>_open (callback)](#apidoc.element.mongoskin.GridStore.prototype._open)
- description and source-code
```javascript
_open = function (callback) {
  var skin_db = this._construct_args[0];
  var args = this._construct_args.slice(1);
  skin_db.open(function(err, p_db) {
      if(err) return callback(err);
      args = ([null, p_db]).concat(args);
      var ctor = GridStore.bind.apply(GridStore, args);
      var gridStore = new ctor();
      gridStore.open(callback);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.chunkCollection"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>chunkCollection ()](#apidoc.element.mongoskin.GridStore.prototype.chunkCollection)
- description and source-code
```javascript
chunkCollection = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>close (callback)](#apidoc.element.mongoskin.GridStore.prototype.close)
- description and source-code
```javascript
close = function (callback) {
  if (this._state === STATE_CLOSE) {
    callback && callback();
  } else if (this._state === STATE_OPEN) {
    this._state = STATE_CLOSE;
    this._close(callback);
  } else if (this._state === STATE_OPENNING) {
    var self = this;
    this._emitter.once('open', function (err, db) {
        self.close(callback);
    });
  }
  this._native = null;
  return this;
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.collection"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>collection ()](#apidoc.element.mongoskin.GridStore.prototype.collection)
- description and source-code
```javascript
collection = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
...
        new Server('localhost', 30000),
        new Server('localhost', 30001),
        new Server('localhost', 30002),
]);

var db = new Db('integration_test_', replSet, {w:0, native_parser: (process.env['TEST_NATIVE'] != null)});
// no need open and on('fullsetup', ...)
db.collection('myconnection').find().setReadPreference(ReadPreference.SECONDARY).toArray(function(err, items) {
        db.close();
});
'''

Model helper:

'''js
...
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.destroy"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>destroy ()](#apidoc.element.mongoskin.GridStore.prototype.destroy)
- description and source-code
```javascript
destroy = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.eof"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>eof ()](#apidoc.element.mongoskin.GridStore.prototype.eof)
- description and source-code
```javascript
eof = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.getc"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>getc ()](#apidoc.element.mongoskin.GridStore.prototype.getc)
- description and source-code
```javascript
getc = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.isOpen"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>isOpen ()](#apidoc.element.mongoskin.GridStore.prototype.isOpen)
- description and source-code
```javascript
isOpen = function () {
  return this._state === STATE_OPEN;
}
```
- example usage
```shell
...
 * @param {Function(err, docs)} callback
 * @return {SkinCursor|SkinCollection} if last argument is not a function, then returns a SkinCursor,
 *   otherise return this
 * @api public
 */
SkinCollection.prototype.find = function (query, options, callback) {
var args = __slice.call(arguments);
if(this.isOpen()) {
  return this._native.find.apply(this._native, args);
}
if (args.length > 0 && typeof args[args.length - 1] === 'function') {
  this._find.apply(this, args);
  return this;
} else {
  var cursor = new SkinCursor();
...
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.open"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>open (callback)](#apidoc.element.mongoskin.GridStore.prototype.open)
- description and source-code
```javascript
open = function (callback) {
  switch (this._state) {
    case STATE_OPEN:
      callback(null, this._native);
      break;
    case STATE_OPENNING:
      this._emitter.once('open', callback);
      break;
    default:
      this._emitter.once('open', callback);
      this._state = STATE_OPENNING;
      var self = this;
      this._open(function(err, p_native) {
          if (err) {
            self._state = STATE_CLOSE;
          } else {
            self._state = STATE_OPEN;
            self._native = p_native;
          }
          self._emitter.emit('open', err, p_native);
      });
  }
  return this;
}
```
- example usage
```shell
...

alias origin 'db.collection(..., function(err, collection) {....})'

origin:

'''js
var db = new Db(...);
db.open(function(err, db) {
    db.collection('myCollection', {strict: true}, function(err, myCollection) {
        // myCollection.find() ...
    });
});
'''

mongoskin:
...
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.puts"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>puts ()](#apidoc.element.mongoskin.GridStore.prototype.puts)
- description and source-code
```javascript
puts = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.read"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>read ()](#apidoc.element.mongoskin.GridStore.prototype.read)
- description and source-code
```javascript
read = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.readlines"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>readlines ()](#apidoc.element.mongoskin.GridStore.prototype.readlines)
- description and source-code
```javascript
readlines = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.rewind"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>rewind ()](#apidoc.element.mongoskin.GridStore.prototype.rewind)
- description and source-code
```javascript
rewind = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.seek"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>seek ()](#apidoc.element.mongoskin.GridStore.prototype.seek)
- description and source-code
```javascript
seek = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.stream"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>stream ()](#apidoc.element.mongoskin.GridStore.prototype.stream)
- description and source-code
```javascript
stream = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.tell"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>tell ()](#apidoc.element.mongoskin.GridStore.prototype.tell)
- description and source-code
```javascript
tell = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.unlink"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>unlink ()](#apidoc.element.mongoskin.GridStore.prototype.unlink)
- description and source-code
```javascript
unlink = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.write"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>write ()](#apidoc.element.mongoskin.GridStore.prototype.write)
- description and source-code
```javascript
write = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.GridStore.prototype.writeFile"></a>[function <span class="apidocSignatureSpan">mongoskin.GridStore.prototype.</span>writeFile ()](#apidoc.element.mongoskin.GridStore.prototype.writeFile)
- description and source-code
```javascript
writeFile = function () {
  var args = __slice.apply(arguments);
  if (this._state == STATE_OPEN) {
    this._native[propName].apply(this._native, args);
  } else {
    this.open(function(err, p_native) {
        if (err) {
          onError(err, args, skinClassName + '.' + propName);
        } else {
          p_native[propName].apply(p_native, args);
        }
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Int32"></a>[module mongoskin.Int32](#apidoc.module.mongoskin.Int32)

#### <a name="apidoc.element.mongoskin.Int32.Int32"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Int32 (value)](#apidoc.element.mongoskin.Int32.Int32)
- description and source-code
```javascript
Int32 = function (value) {
  if(!(this instanceof Int32)) return new Int32(value);

  this._bsontype = 'Int32';
  this.value = value;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Int32.prototype"></a>[module mongoskin.Int32.prototype](#apidoc.module.mongoskin.Int32.prototype)

#### <a name="apidoc.element.mongoskin.Int32.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.Int32.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Int32.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Int32.prototype.valueOf"></a>[function <span class="apidocSignatureSpan">mongoskin.Int32.prototype.</span>valueOf ()](#apidoc.element.mongoskin.Int32.prototype.valueOf)
- description and source-code
```javascript
valueOf = function () {
  return this.value;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Logger"></a>[module mongoskin.Logger](#apidoc.module.mongoskin.Logger)

#### <a name="apidoc.element.mongoskin.Logger.Logger"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Logger (className, options)](#apidoc.element.mongoskin.Logger.Logger)
- description and source-code
```javascript
Logger = function (className, options) {
  if(!(this instanceof Logger)) return new Logger(className, options);
  options = options || {};

  // Current reference
  this.className = className;

  // Current logger
  if(options.logger) {
    currentLogger = options.logger;
  } else if(currentLogger == null) {
    currentLogger = console.log;
  }

  // Set level of logging, default is error
  if(options.loggerLevel) {
    level = options.loggerLevel || 'error';
  }

  // Add all class names
  if(filteredClasses[this.className] == null) classFilters[this.className] =  true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.currentLogger"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.</span>currentLogger ()](#apidoc.element.mongoskin.Logger.currentLogger)
- description and source-code
```javascript
currentLogger = function () {
  return currentLogger;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.filter"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.</span>filter (type, values)](#apidoc.element.mongoskin.Logger.filter)
- description and source-code
```javascript
filter = function (type, values) {
  if(type == 'class' && Array.isArray(values)) {
    filteredClasses = {};

    values.forEach(function(x) {
      filteredClasses[x] = true;
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.reset"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.</span>reset ()](#apidoc.element.mongoskin.Logger.reset)
- description and source-code
```javascript
reset = function () {
  level = 'error';
  filteredClasses = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.setCurrentLogger"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.</span>setCurrentLogger (logger)](#apidoc.element.mongoskin.Logger.setCurrentLogger)
- description and source-code
```javascript
setCurrentLogger = function (logger) {
  if(typeof logger != 'function') throw new MongoError("current logger must be a function");
  currentLogger = logger;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.setLevel"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.</span>setLevel (_level)](#apidoc.element.mongoskin.Logger.setLevel)
- description and source-code
```javascript
setLevel = function (_level) {
  if(_level != 'info' && _level != 'error' && _level != 'debug' && _level != 'warn') {
    throw new Error(f("%s is an illegal logging level", _level));
  }

  level = _level;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Logger.prototype"></a>[module mongoskin.Logger.prototype](#apidoc.module.mongoskin.Logger.prototype)

#### <a name="apidoc.element.mongoskin.Logger.prototype.debug"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>debug (message, object)](#apidoc.element.mongoskin.Logger.prototype.debug)
- description and source-code
```javascript
debug = function (message, object) {
  if(this.isDebug()
    && ((Object.keys(filteredClasses).length > 0 && filteredClasses[this.className])
      || (Object.keys(filteredClasses).length == 0 && classFilters[this.className]))) {
    var dateTime = new Date().getTime();
    var msg = f("[%s-%s:%s] %s %s", 'DEBUG', this.className, pid, dateTime, message);
    var state = {
      type: 'debug', message: message, className: this.className, pid: pid, date: dateTime
    };
    if(object) state.meta = object;
    currentLogger(msg, state);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.prototype.error"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>error (message, object)](#apidoc.element.mongoskin.Logger.prototype.error)
- description and source-code
```javascript
error = function (message, object) {
  if(this.isError()
    && ((Object.keys(filteredClasses).length > 0 && filteredClasses[this.className])
      || (Object.keys(filteredClasses).length == 0 && classFilters[this.className]))) {
    var dateTime = new Date().getTime();
    var msg = f("[%s-%s:%s] %s %s", 'ERROR', this.className, pid, dateTime, message);
    var state = {
      type: 'error', message: message, className: this.className, pid: pid, date: dateTime
    };
    if(object) state.meta = object;
    currentLogger(msg, state);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.prototype.info"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>info (message, object)](#apidoc.element.mongoskin.Logger.prototype.info)
- description and source-code
```javascript
info = function (message, object) {
  if(this.isInfo()
    && ((Object.keys(filteredClasses).length > 0 && filteredClasses[this.className])
      || (Object.keys(filteredClasses).length == 0 && classFilters[this.className]))) {
    var dateTime = new Date().getTime();
    var msg = f("[%s-%s:%s] %s %s", 'INFO', this.className, pid, dateTime, message);
    var state = {
      type: 'info', message: message, className: this.className, pid: pid, date: dateTime
    };
    if(object) state.meta = object;
    currentLogger(msg, state);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.prototype.isDebug"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>isDebug ()](#apidoc.element.mongoskin.Logger.prototype.isDebug)
- description and source-code
```javascript
isDebug = function () {
  return level == 'debug';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.prototype.isError"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>isError ()](#apidoc.element.mongoskin.Logger.prototype.isError)
- description and source-code
```javascript
isError = function () {
  return level == 'error' || level == 'info' || level == 'debug';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.prototype.isInfo"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>isInfo ()](#apidoc.element.mongoskin.Logger.prototype.isInfo)
- description and source-code
```javascript
isInfo = function () {
  return level == 'info' || level == 'debug';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.prototype.isWarn"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>isWarn ()](#apidoc.element.mongoskin.Logger.prototype.isWarn)
- description and source-code
```javascript
isWarn = function () {
  return level == 'error' || level == 'warn' || level == 'info' || level == 'debug';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Logger.prototype.warn"></a>[function <span class="apidocSignatureSpan">mongoskin.Logger.prototype.</span>warn (message, object)](#apidoc.element.mongoskin.Logger.prototype.warn)
- description and source-code
```javascript
warn = function (message, object) {
  if(this.isWarn()
    && ((Object.keys(filteredClasses).length > 0 && filteredClasses[this.className])
      || (Object.keys(filteredClasses).length == 0 && classFilters[this.className]))) {
    var dateTime = new Date().getTime();
    var msg = f("[%s-%s:%s] %s %s", 'WARN', this.className, pid, dateTime, message);
    var state = {
      type: 'warn', message: message, className: this.className, pid: pid, date: dateTime
    };
    if(object) state.meta = object;
    currentLogger(msg, state);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Long"></a>[module mongoskin.Long](#apidoc.module.mongoskin.Long)

#### <a name="apidoc.element.mongoskin.Long.Long"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Long (low, high)](#apidoc.element.mongoskin.Long.Long)
- description and source-code
```javascript
function Long(low, high) {
  if(!(this instanceof Long)) return new Long(low, high);

  this._bsontype = 'Long';
<span class="apidocCodeCommentSpan">  /**
   * @type {number}
   * @ignore
   */
</span>  this.low_ = low | 0;  // force into 32 signed bits.

  /**
   * @type {number}
   * @ignore
   */
  this.high_ = high | 0;  // force into 32 signed bits.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.fromBits"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.</span>fromBits (lowBits, highBits)](#apidoc.element.mongoskin.Long.fromBits)
- description and source-code
```javascript
fromBits = function (lowBits, highBits) {
  return new Long(lowBits, highBits);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.fromInt"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.</span>fromInt (value)](#apidoc.element.mongoskin.Long.fromInt)
- description and source-code
```javascript
fromInt = function (value) {
  if (-128 <= value && value < 128) {
    var cachedObj = Long.INT_CACHE_[value];
    if (cachedObj) {
      return cachedObj;
    }
  }

  var obj = new Long(value | 0, value < 0 ? -1 : 0);
  if (-128 <= value && value < 128) {
    Long.INT_CACHE_[value] = obj;
  }
  return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.fromNumber"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.</span>fromNumber (value)](#apidoc.element.mongoskin.Long.fromNumber)
- description and source-code
```javascript
fromNumber = function (value) {
  if (isNaN(value) || !isFinite(value)) {
    return Long.ZERO;
  } else if (value <= -Long.TWO_PWR_63_DBL_) {
    return Long.MIN_VALUE;
  } else if (value + 1 >= Long.TWO_PWR_63_DBL_) {
    return Long.MAX_VALUE;
  } else if (value < 0) {
    return Long.fromNumber(-value).negate();
  } else {
    return new Long(
               (value % Long.TWO_PWR_32_DBL_) | 0,
               (value / Long.TWO_PWR_32_DBL_) | 0);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.fromString"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.</span>fromString (str, opt_radix)](#apidoc.element.mongoskin.Long.fromString)
- description and source-code
```javascript
fromString = function (str, opt_radix) {
  if (str.length == 0) {
    throw Error('number format error: empty string');
  }

  var radix = opt_radix || 10;
  if (radix < 2 || 36 < radix) {
    throw Error('radix out of range: ' + radix);
  }

  if (str.charAt(0) == '-') {
    return Long.fromString(str.substring(1), radix).negate();
  } else if (str.indexOf('-') >= 0) {
    throw Error('number format error: interior "-" character: ' + str);
  }

  // Do several (8) digits each time through the loop, so as to
  // minimize the calls to the very expensive emulated div.
  var radixToPower = Long.fromNumber(Math.pow(radix, 8));

  var result = Long.ZERO;
  for (var i = 0; i < str.length; i += 8) {
    var size = Math.min(8, str.length - i);
    var value = parseInt(str.substring(i, i + size), radix);
    if (size < 8) {
      var power = Long.fromNumber(Math.pow(radix, size));
      result = result.multiply(power).add(Long.fromNumber(value));
    } else {
      result = result.multiply(radixToPower);
      result = result.add(Long.fromNumber(value));
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Long.prototype"></a>[module mongoskin.Long.prototype](#apidoc.module.mongoskin.Long.prototype)

#### <a name="apidoc.element.mongoskin.Long.prototype.add"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>add (other)](#apidoc.element.mongoskin.Long.prototype.add)
- description and source-code
```javascript
add = function (other) {
  // Divide each number into 4 chunks of 16 bits, and then sum the chunks.

  var a48 = this.high_ >>> 16;
  var a32 = this.high_ & 0xFFFF;
  var a16 = this.low_ >>> 16;
  var a00 = this.low_ & 0xFFFF;

  var b48 = other.high_ >>> 16;
  var b32 = other.high_ & 0xFFFF;
  var b16 = other.low_ >>> 16;
  var b00 = other.low_ & 0xFFFF;

  var c48 = 0, c32 = 0, c16 = 0, c00 = 0;
  c00 += a00 + b00;
  c16 += c00 >>> 16;
  c00 &= 0xFFFF;
  c16 += a16 + b16;
  c32 += c16 >>> 16;
  c16 &= 0xFFFF;
  c32 += a32 + b32;
  c48 += c32 >>> 16;
  c32 &= 0xFFFF;
  c48 += a48 + b48;
  c48 &= 0xFFFF;
  return Long.fromBits((c16 << 16) | c00, (c48 << 16) | c32);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.and"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>and (other)](#apidoc.element.mongoskin.Long.prototype.and)
- description and source-code
```javascript
and = function (other) {
  return Long.fromBits(this.low_ & other.low_, this.high_ & other.high_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.compare"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>compare (other)](#apidoc.element.mongoskin.Long.prototype.compare)
- description and source-code
```javascript
compare = function (other) {
  if (this.equals(other)) {
    return 0;
  }

  var thisNeg = this.isNegative();
  var otherNeg = other.isNegative();
  if (thisNeg && !otherNeg) {
    return -1;
  }
  if (!thisNeg && otherNeg) {
    return 1;
  }

  // at this point, the signs are the same, so subtraction will not overflow
  if (this.subtract(other).isNegative()) {
    return -1;
  } else {
    return 1;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.div"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>div (other)](#apidoc.element.mongoskin.Long.prototype.div)
- description and source-code
```javascript
div = function (other) {
  if (other.isZero()) {
    throw Error('division by zero');
  } else if (this.isZero()) {
    return Long.ZERO;
  }

  if (this.equals(Long.MIN_VALUE)) {
    if (other.equals(Long.ONE) ||
        other.equals(Long.NEG_ONE)) {
      return Long.MIN_VALUE;  // recall that -MIN_VALUE == MIN_VALUE
    } else if (other.equals(Long.MIN_VALUE)) {
      return Long.ONE;
    } else {
      // At this point, we have |other| >= 2, so |this/other| < |MIN_VALUE|.
      var halfThis = this.shiftRight(1);
      var approx = halfThis.div(other).shiftLeft(1);
      if (approx.equals(Long.ZERO)) {
        return other.isNegative() ? Long.ONE : Long.NEG_ONE;
      } else {
        var rem = this.subtract(other.multiply(approx));
        var result = approx.add(rem.div(other));
        return result;
      }
    }
  } else if (other.equals(Long.MIN_VALUE)) {
    return Long.ZERO;
  }

  if (this.isNegative()) {
    if (other.isNegative()) {
      return this.negate().div(other.negate());
    } else {
      return this.negate().div(other).negate();
    }
  } else if (other.isNegative()) {
    return this.div(other.negate()).negate();
  }

  // Repeat the following until the remainder is less than other:  find a
  // floating-point that approximates remainder / other *from below*, add this
  // into the result, and subtract it from the remainder.  It is critical that
  // the approximate value is less than or equal to the real value so that the
  // remainder never becomes negative.
  var res = Long.ZERO;
  var rem = this;
  while (rem.greaterThanOrEqual(other)) {
    // Approximate the result of division. This may be a little greater or
    // smaller than the actual value.
    var approx = Math.max(1, Math.floor(rem.toNumber() / other.toNumber()));

    // We will tweak the approximate result by changing it in the 48-th digit or
    // the smallest non-fractional digit, whichever is larger.
    var log2 = Math.ceil(Math.log(approx) / Math.LN2);
    var delta = (log2 <= 48) ? 1 : Math.pow(2, log2 - 48);

    // Decrease the approximation until it is smaller than the remainder.  Note
    // that if it is too large, the product overflows and is negative.
    var approxRes = Long.fromNumber(approx);
    var approxRem = approxRes.multiply(other);
    while (approxRem.isNegative() || approxRem.greaterThan(rem)) {
      approx -= delta;
      approxRes = Long.fromNumber(approx);
      approxRem = approxRes.multiply(other);
    }

    // We know the answer can't be zero... and actually, zero would cause
    // infinite recursion since we would make no progress.
    if (approxRes.isZero()) {
      approxRes = Long.ONE;
    }

    res = res.add(approxRes);
    rem = rem.subtract(approxRem);
  }
  return res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.equals"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>equals (other)](#apidoc.element.mongoskin.Long.prototype.equals)
- description and source-code
```javascript
equals = function (other) {
  return (this.high_ == other.high_) && (this.low_ == other.low_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.getHighBits"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>getHighBits ()](#apidoc.element.mongoskin.Long.prototype.getHighBits)
- description and source-code
```javascript
getHighBits = function () {
  return this.high_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.getLowBits"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>getLowBits ()](#apidoc.element.mongoskin.Long.prototype.getLowBits)
- description and source-code
```javascript
getLowBits = function () {
  return this.low_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.getLowBitsUnsigned"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>getLowBitsUnsigned ()](#apidoc.element.mongoskin.Long.prototype.getLowBitsUnsigned)
- description and source-code
```javascript
getLowBitsUnsigned = function () {
  return (this.low_ >= 0) ?
      this.low_ : Long.TWO_PWR_32_DBL_ + this.low_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.getNumBitsAbs"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>getNumBitsAbs ()](#apidoc.element.mongoskin.Long.prototype.getNumBitsAbs)
- description and source-code
```javascript
getNumBitsAbs = function () {
  if (this.isNegative()) {
    if (this.equals(Long.MIN_VALUE)) {
      return 64;
    } else {
      return this.negate().getNumBitsAbs();
    }
  } else {
    var val = this.high_ != 0 ? this.high_ : this.low_;
    for (var bit = 31; bit > 0; bit--) {
      if ((val & (1 << bit)) != 0) {
        break;
      }
    }
    return this.high_ != 0 ? bit + 33 : bit + 1;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.greaterThan"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>greaterThan (other)](#apidoc.element.mongoskin.Long.prototype.greaterThan)
- description and source-code
```javascript
greaterThan = function (other) {
  return this.compare(other) > 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.greaterThanOrEqual"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>greaterThanOrEqual (other)](#apidoc.element.mongoskin.Long.prototype.greaterThanOrEqual)
- description and source-code
```javascript
greaterThanOrEqual = function (other) {
  return this.compare(other) >= 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.isNegative"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>isNegative ()](#apidoc.element.mongoskin.Long.prototype.isNegative)
- description and source-code
```javascript
isNegative = function () {
  return this.high_ < 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.isOdd"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>isOdd ()](#apidoc.element.mongoskin.Long.prototype.isOdd)
- description and source-code
```javascript
isOdd = function () {
  return (this.low_ & 1) == 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.isZero"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>isZero ()](#apidoc.element.mongoskin.Long.prototype.isZero)
- description and source-code
```javascript
isZero = function () {
  return this.high_ == 0 && this.low_ == 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.lessThan"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>lessThan (other)](#apidoc.element.mongoskin.Long.prototype.lessThan)
- description and source-code
```javascript
lessThan = function (other) {
  return this.compare(other) < 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.lessThanOrEqual"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>lessThanOrEqual (other)](#apidoc.element.mongoskin.Long.prototype.lessThanOrEqual)
- description and source-code
```javascript
lessThanOrEqual = function (other) {
  return this.compare(other) <= 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.modulo"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>modulo (other)](#apidoc.element.mongoskin.Long.prototype.modulo)
- description and source-code
```javascript
modulo = function (other) {
  return this.subtract(this.div(other).multiply(other));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.multiply"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>multiply (other)](#apidoc.element.mongoskin.Long.prototype.multiply)
- description and source-code
```javascript
multiply = function (other) {
  if (this.isZero()) {
    return Long.ZERO;
  } else if (other.isZero()) {
    return Long.ZERO;
  }

  if (this.equals(Long.MIN_VALUE)) {
    return other.isOdd() ? Long.MIN_VALUE : Long.ZERO;
  } else if (other.equals(Long.MIN_VALUE)) {
    return this.isOdd() ? Long.MIN_VALUE : Long.ZERO;
  }

  if (this.isNegative()) {
    if (other.isNegative()) {
      return this.negate().multiply(other.negate());
    } else {
      return this.negate().multiply(other).negate();
    }
  } else if (other.isNegative()) {
    return this.multiply(other.negate()).negate();
  }

  // If both Longs are small, use float multiplication
  if (this.lessThan(Long.TWO_PWR_24_) &&
      other.lessThan(Long.TWO_PWR_24_)) {
    return Long.fromNumber(this.toNumber() * other.toNumber());
  }

  // Divide each Long into 4 chunks of 16 bits, and then add up 4x4 products.
  // We can skip products that would overflow.

  var a48 = this.high_ >>> 16;
  var a32 = this.high_ & 0xFFFF;
  var a16 = this.low_ >>> 16;
  var a00 = this.low_ & 0xFFFF;

  var b48 = other.high_ >>> 16;
  var b32 = other.high_ & 0xFFFF;
  var b16 = other.low_ >>> 16;
  var b00 = other.low_ & 0xFFFF;

  var c48 = 0, c32 = 0, c16 = 0, c00 = 0;
  c00 += a00 * b00;
  c16 += c00 >>> 16;
  c00 &= 0xFFFF;
  c16 += a16 * b00;
  c32 += c16 >>> 16;
  c16 &= 0xFFFF;
  c16 += a00 * b16;
  c32 += c16 >>> 16;
  c16 &= 0xFFFF;
  c32 += a32 * b00;
  c48 += c32 >>> 16;
  c32 &= 0xFFFF;
  c32 += a16 * b16;
  c48 += c32 >>> 16;
  c32 &= 0xFFFF;
  c32 += a00 * b32;
  c48 += c32 >>> 16;
  c32 &= 0xFFFF;
  c48 += a48 * b00 + a32 * b16 + a16 * b32 + a00 * b48;
  c48 &= 0xFFFF;
  return Long.fromBits((c16 << 16) | c00, (c48 << 16) | c32);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.negate"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>negate ()](#apidoc.element.mongoskin.Long.prototype.negate)
- description and source-code
```javascript
negate = function () {
  if (this.equals(Long.MIN_VALUE)) {
    return Long.MIN_VALUE;
  } else {
    return this.not().add(Long.ONE);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.not"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>not ()](#apidoc.element.mongoskin.Long.prototype.not)
- description and source-code
```javascript
not = function () {
  return Long.fromBits(~this.low_, ~this.high_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.notEquals"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>notEquals (other)](#apidoc.element.mongoskin.Long.prototype.notEquals)
- description and source-code
```javascript
notEquals = function (other) {
  return (this.high_ != other.high_) || (this.low_ != other.low_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.or"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>or (other)](#apidoc.element.mongoskin.Long.prototype.or)
- description and source-code
```javascript
or = function (other) {
  return Long.fromBits(this.low_ | other.low_, this.high_ | other.high_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.shiftLeft"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>shiftLeft (numBits)](#apidoc.element.mongoskin.Long.prototype.shiftLeft)
- description and source-code
```javascript
shiftLeft = function (numBits) {
  numBits &= 63;
  if (numBits == 0) {
    return this;
  } else {
    var low = this.low_;
    if (numBits < 32) {
      var high = this.high_;
      return Long.fromBits(
                 low << numBits,
                 (high << numBits) | (low >>> (32 - numBits)));
    } else {
      return Long.fromBits(0, low << (numBits - 32));
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.shiftRight"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>shiftRight (numBits)](#apidoc.element.mongoskin.Long.prototype.shiftRight)
- description and source-code
```javascript
shiftRight = function (numBits) {
  numBits &= 63;
  if (numBits == 0) {
    return this;
  } else {
    var high = this.high_;
    if (numBits < 32) {
      var low = this.low_;
      return Long.fromBits(
                 (low >>> numBits) | (high << (32 - numBits)),
                 high >> numBits);
    } else {
      return Long.fromBits(
                 high >> (numBits - 32),
                 high >= 0 ? 0 : -1);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.shiftRightUnsigned"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>shiftRightUnsigned (numBits)](#apidoc.element.mongoskin.Long.prototype.shiftRightUnsigned)
- description and source-code
```javascript
shiftRightUnsigned = function (numBits) {
  numBits &= 63;
  if (numBits == 0) {
    return this;
  } else {
    var high = this.high_;
    if (numBits < 32) {
      var low = this.low_;
      return Long.fromBits(
                 (low >>> numBits) | (high << (32 - numBits)),
                 high >>> numBits);
    } else if (numBits == 32) {
      return Long.fromBits(high, 0);
    } else {
      return Long.fromBits(high >>> (numBits - 32), 0);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.subtract"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>subtract (other)](#apidoc.element.mongoskin.Long.prototype.subtract)
- description and source-code
```javascript
subtract = function (other) {
  return this.add(other.negate());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.toInt"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>toInt ()](#apidoc.element.mongoskin.Long.prototype.toInt)
- description and source-code
```javascript
toInt = function () {
  return this.low_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Long.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.toString();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.toNumber"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>toNumber ()](#apidoc.element.mongoskin.Long.prototype.toNumber)
- description and source-code
```javascript
toNumber = function () {
  return this.high_ * Long.TWO_PWR_32_DBL_ +
         this.getLowBitsUnsigned();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.toString"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>toString (opt_radix)](#apidoc.element.mongoskin.Long.prototype.toString)
- description and source-code
```javascript
toString = function (opt_radix) {
  var radix = opt_radix || 10;
  if (radix < 2 || 36 < radix) {
    throw Error('radix out of range: ' + radix);
  }

  if (this.isZero()) {
    return '0';
  }

  if (this.isNegative()) {
    if (this.equals(Long.MIN_VALUE)) {
      // We need to change the Long value before it can be negated, so we remove
      // the bottom-most digit in this base and then recurse to do the rest.
      var radixLong = Long.fromNumber(radix);
      var div = this.div(radixLong);
      var rem = div.multiply(radixLong).subtract(this);
      return div.toString(radix) + rem.toInt().toString(radix);
    } else {
      return '-' + this.negate().toString(radix);
    }
  }

  // Do several (6) digits each time through the loop, so as to
  // minimize the calls to the very expensive emulated div.
  var radixToPower = Long.fromNumber(Math.pow(radix, 6));

  var rem = this;
  var result = '';
  while (true) {
    var remDiv = rem.div(radixToPower);
    var intval = rem.subtract(remDiv.multiply(radixToPower)).toInt();
    var digits = intval.toString(radix);

    rem = remDiv;
    if (rem.isZero()) {
      return digits + result;
    } else {
      while (digits.length < 6) {
        digits = '0' + digits;
      }
      result = '' + digits + result;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Long.prototype.xor"></a>[function <span class="apidocSignatureSpan">mongoskin.Long.prototype.</span>xor (other)](#apidoc.element.mongoskin.Long.prototype.xor)
- description and source-code
```javascript
xor = function (other) {
  return Long.fromBits(this.low_ ^ other.low_, this.high_ ^ other.high_);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Map"></a>[module mongoskin.Map](#apidoc.module.mongoskin.Map)

#### <a name="apidoc.element.mongoskin.Map.Map"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Map ()](#apidoc.element.mongoskin.Map.Map)
- description and source-code
```javascript
function Map() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.MaxKey"></a>[module mongoskin.MaxKey](#apidoc.module.mongoskin.MaxKey)

#### <a name="apidoc.element.mongoskin.MaxKey.MaxKey"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>MaxKey ()](#apidoc.element.mongoskin.MaxKey.MaxKey)
- description and source-code
```javascript
function MaxKey() {
  if(!(this instanceof MaxKey)) return new MaxKey();

  this._bsontype = 'MaxKey';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.MinKey"></a>[module mongoskin.MinKey](#apidoc.module.mongoskin.MinKey)

#### <a name="apidoc.element.mongoskin.MinKey.MinKey"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>MinKey ()](#apidoc.element.mongoskin.MinKey.MinKey)
- description and source-code
```javascript
function MinKey() {
  if(!(this instanceof MinKey)) return new MinKey();

  this._bsontype = 'MinKey';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.MongoClient"></a>[module mongoskin.MongoClient](#apidoc.module.mongoskin.MongoClient)

#### <a name="apidoc.element.mongoskin.MongoClient.MongoClient"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>MongoClient ()](#apidoc.element.mongoskin.MongoClient.MongoClient)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.MongoClient._bindGetter"></a>[function <span class="apidocSignatureSpan">mongoskin.MongoClient.</span>_bindGetter (propName)](#apidoc.element.mongoskin.MongoClient._bindGetter)
- description and source-code
```javascript
_bindGetter = function (propName) {
    SkinClass.prototype.__defineGetter__(propName, function() {
        return this._native && this._native[propName];// || this['_prop_' + propName];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.MongoClient._bindMethod"></a>[function <span class="apidocSignatureSpan">mongoskin.MongoClient.</span>_bindMethod (propName)](#apidoc.element.mongoskin.MongoClient._bindMethod)
- description and source-code
```javascript
_bindMethod = function (propName) {
  SkinClass.prototype[propName] = function() {
    var args = __slice.apply(arguments);
    if (this._state == STATE_OPEN) {
      this._native[propName].apply(this._native, args);
    } else {
      this.open(function(err, p_native) {
          if (err) {
            onError(err, args, skinClassName + '.' + propName);
          } else {
            p_native[propName].apply(p_native, args);
          }
      });
    }
    return this;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.MongoClient._bindSetter"></a>[function <span class="apidocSignatureSpan">mongoskin.MongoClient.</span>_bindSetter (propName)](#apidoc.element.mongoskin.MongoClient._bindSetter)
- description and source-code
```javascript
_bindSetter = function (propName) {
    SkinClass.prototype.__defineSetter__(propName, function(value) {
        // this['_prop_' + propName] = value;
        this.open(function(err, p_native) {
            if(err) return onError(err, args, skinClassName + '.' + propName);
            p_native[propName] = value;
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.MongoClient.connect"></a>[function <span class="apidocSignatureSpan">mongoskin.MongoClient.</span>connect ()](#apidoc.element.mongoskin.MongoClient.connect)
- description and source-code
```javascript
connect = function () {
  var args = [].slice.call(arguments);
  var db = new SkinDb();
  db._connect_args = args;
  return db;
}
```
- example usage
```shell
...
var Db = mongo.Db;
var Server = mongo.Server;
var MongoClient = mongo.MongoClient;
var ReplSetServers = mongo.ReplSetServers;
...
'''

### MongoClient.connect(...)

returns a 'Db' instance

alias origin 'MongoClient.connect(..., function(err, db) { .... })'

origin:
...
```



# <a name="apidoc.module.mongoskin.MongoClient.prototype"></a>[module mongoskin.MongoClient.prototype](#apidoc.module.mongoskin.MongoClient.prototype)

#### <a name="apidoc.element.mongoskin.MongoClient.prototype._close"></a>[function <span class="apidocSignatureSpan">mongoskin.MongoClient.prototype.</span>_close (callback)](#apidoc.element.mongoskin.MongoClient.prototype._close)
- description and source-code
```javascript
_close = function (callback) {
  if(this._native.close) {
    this._native.close(callback)
  } else if(callback) {
    callback();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.MongoClient.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.MongoClient.prototype.</span>close (callback)](#apidoc.element.mongoskin.MongoClient.prototype.close)
- description and source-code
```javascript
close = function (callback) {
  if (this._state === STATE_CLOSE) {
    callback && callback();
  } else if (this._state === STATE_OPEN) {
    this._state = STATE_CLOSE;
    this._close(callback);
  } else if (this._state === STATE_OPENNING) {
    var self = this;
    this._emitter.once('open', function (err, db) {
        self.close(callback);
    });
  }
  this._native = null;
  return this;
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.MongoClient.prototype.isOpen"></a>[function <span class="apidocSignatureSpan">mongoskin.MongoClient.prototype.</span>isOpen ()](#apidoc.element.mongoskin.MongoClient.prototype.isOpen)
- description and source-code
```javascript
isOpen = function () {
  return this._state === STATE_OPEN;
}
```
- example usage
```shell
...
 * @param {Function(err, docs)} callback
 * @return {SkinCursor|SkinCollection} if last argument is not a function, then returns a SkinCursor,
 *   otherise return this
 * @api public
 */
SkinCollection.prototype.find = function (query, options, callback) {
var args = __slice.call(arguments);
if(this.isOpen()) {
  return this._native.find.apply(this._native, args);
}
if (args.length > 0 && typeof args[args.length - 1] === 'function') {
  this._find.apply(this, args);
  return this;
} else {
  var cursor = new SkinCursor();
...
```

#### <a name="apidoc.element.mongoskin.MongoClient.prototype.open"></a>[function <span class="apidocSignatureSpan">mongoskin.MongoClient.prototype.</span>open (callback)](#apidoc.element.mongoskin.MongoClient.prototype.open)
- description and source-code
```javascript
open = function (callback) {
  switch (this._state) {
    case STATE_OPEN:
      callback(null, this._native);
      break;
    case STATE_OPENNING:
      this._emitter.once('open', callback);
      break;
    default:
      this._emitter.once('open', callback);
      this._state = STATE_OPENNING;
      var self = this;
      this._open(function(err, p_native) {
          if (err) {
            self._state = STATE_CLOSE;
          } else {
            self._state = STATE_OPEN;
            self._native = p_native;
          }
          self._emitter.emit('open', err, p_native);
      });
  }
  return this;
}
```
- example usage
```shell
...

alias origin 'db.collection(..., function(err, collection) {....})'

origin:

'''js
var db = new Db(...);
db.open(function(err, db) {
    db.collection('myCollection', {strict: true}, function(err, myCollection) {
        // myCollection.find() ...
    });
});
'''

mongoskin:
...
```



# <a name="apidoc.module.mongoskin.MongoError"></a>[module mongoskin.MongoError](#apidoc.module.mongoskin.MongoError)

#### <a name="apidoc.element.mongoskin.MongoError.MongoError"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>MongoError (message)](#apidoc.element.mongoskin.MongoError.MongoError)
- description and source-code
```javascript
function MongoError(message) {
  this.name = 'MongoError';
  this.message = message;
  Error.captureStackTrace(this, MongoError);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.MongoError.create"></a>[function <span class="apidocSignatureSpan">mongoskin.MongoError.</span>create (options)](#apidoc.element.mongoskin.MongoError.create)
- description and source-code
```javascript
create = function (options) {
  var err = null;

  if(options instanceof Error) {
    err = new MongoError(options.message);
    err.stack = options.stack;
  } else if(typeof options == 'string') {
    err = new MongoError(options);
  } else {
    err = new MongoError(options.message || options.errmsg || options.$err || "n/a");
    // Other options
    for(var name in options) {
      err[name] = options[name];
    }
  }

  return err;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Mongos"></a>[module mongoskin.Mongos](#apidoc.module.mongoskin.Mongos)

#### <a name="apidoc.element.mongoskin.Mongos.Mongos"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Mongos (servers, options)](#apidoc.element.mongoskin.Mongos.Mongos)
- description and source-code
```javascript
Mongos = function (servers, options) {
  if(!(this instanceof Mongos)) return new Mongos(servers, options);
  options = options || {};
  var self = this;

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Ensure all the instances are Server
  for(var i = 0; i < servers.length; i++) {
    if(!(servers[i] instanceof Server)) {
      throw MongoError.create({message: "all seed list instances must be of the Server type", driver:true});
    }
  }

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Set up event emitter
  EventEmitter.call(this);

  // Build seed list
  var seedlist = servers.map(function(x) {
    return {host: x.host, port: x.port}
  });

  // Get the reconnect option
  var reconnect = typeof options.auto_reconnect == 'boolean' ? options.auto_reconnect : true;
  reconnect = typeof options.autoReconnect == 'boolean' ? options.autoReconnect : reconnect;

  // Clone options
  var clonedOptions = mergeOptions({}, {
    disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: reconnect,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Build default client information
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create the Mongos
  var mongos = new CMongos(seedlist, clonedOptions)
  // Server capabilities
  var sCapabilities = null;

  // Internal state
  this.s = {
    // Create the Mongos
      mongos: mongos
    // Server capabilities
    , sCapabilities: sCapabilities
    // Debug turned on
    , debug: clonedOptions.debug
    // Store option defaults
    , storeOptions: storeOptions
    // Cloned options
    , clonedOptions: clonedOptions
    // Actual store of callbacks
    , store: store
    // Options
    , options: options
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.super_"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.</span>super_ ()](#apidoc.element.mongoskin.Mongos.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Mongos.define"></a>[module mongoskin.Mongos.define](#apidoc.module.mongoskin.Mongos.define)

#### <a name="apidoc.element.mongoskin.Mongos.define.object"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.define.</span>object (servers, options)](#apidoc.element.mongoskin.Mongos.define.object)
- description and source-code
```javascript
object = function (servers, options) {
  if(!(this instanceof Mongos)) return new Mongos(servers, options);
  options = options || {};
  var self = this;

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Ensure all the instances are Server
  for(var i = 0; i < servers.length; i++) {
    if(!(servers[i] instanceof Server)) {
      throw MongoError.create({message: "all seed list instances must be of the Server type", driver:true});
    }
  }

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Set up event emitter
  EventEmitter.call(this);

  // Build seed list
  var seedlist = servers.map(function(x) {
    return {host: x.host, port: x.port}
  });

  // Get the reconnect option
  var reconnect = typeof options.auto_reconnect == 'boolean' ? options.auto_reconnect : true;
  reconnect = typeof options.autoReconnect == 'boolean' ? options.autoReconnect : reconnect;

  // Clone options
  var clonedOptions = mergeOptions({}, {
    disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: reconnect,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Build default client information
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create the Mongos
  var mongos = new CMongos(seedlist, clonedOptions)
  // Server capabilities
  var sCapabilities = null;

  // Internal state
  this.s = {
    // Create the Mongos
      mongos: mongos
    // Server capabilities
    , sCapabilities: sCapabilities
    // Debug turned on
    , debug: clonedOptions.debug
    // Store option defaults
    , storeOptions: storeOptions
    // Cloned options
    , clonedOptions: clonedOptions
    // Actual store of callbacks
    , store: store
    // Options
    , options: options
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Mongos.prototype"></a>[module mongoskin.Mongos.prototype](#apidoc.module.mongoskin.Mongos.prototype)

#### <a name="apidoc.element.mongoskin.Mongos.prototype.auth"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>auth ()](#apidoc.element.mongoskin.Mongos.prototype.auth)
- description and source-code
```javascript
auth = function () {
  var args = Array.prototype.slice.call(arguments, 0);
  this.s.mongos.auth.apply(this.s.mongos, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.capabilities"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>capabilities ()](#apidoc.element.mongoskin.Mongos.prototype.capabilities)
- description and source-code
```javascript
capabilities = function () {
  if(this.s.sCapabilities) return this.s.sCapabilities;
  if(this.s.mongos.lastIsMaster() == null) return null;
  this.s.sCapabilities = new ServerCapabilities(this.s.mongos.lastIsMaster());
  return this.s.sCapabilities;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>close (forceClosed)](#apidoc.element.mongoskin.Mongos.prototype.close)
- description and source-code
```javascript
close = function (forceClosed) {
  this.s.mongos.destroy({
    force: typeof forceClosed == 'boolean' ? forceClosed : false,
  });
  // We need to wash out all stored processes
  if(forceClosed == true) {
    this.s.storeOptions.force = forceClosed;
    this.s.store.flush();
  }
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.command"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>command (ns, cmd, options, callback)](#apidoc.element.mongoskin.Mongos.prototype.command)
- description and source-code
```javascript
command = function (ns, cmd, options, callback) {
  this.s.mongos.command(ns, cmd, getReadPreference(options), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.connect"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>connect (db, _options, callback)](#apidoc.element.mongoskin.Mongos.prototype.connect)
- description and source-code
```javascript
connect = function (db, _options, callback) {
  var self = this;
  if('function' === typeof _options) callback = _options, _options = {};
  if(_options == null) _options = {};
  if(!('function' === typeof callback)) callback = null;
  self.s.options = _options;

  // Update bufferMaxEntries
  self.s.storeOptions.bufferMaxEntries = db.bufferMaxEntries;

  // Error handler
  var connectErrorHandler = function() {
    return function(err) {
      // Remove all event handlers
      var events = ['timeout', 'error', 'close'];
      events.forEach(function(e) {
        self.removeListener(e, connectErrorHandler);
      });

      self.s.mongos.removeListener('connect', connectErrorHandler);

      // Try to callback
      try {
        callback(err);
      } catch(err) {
        process.nextTick(function() { throw err; })
      }
    }
  }

  // Actual handler
  var errorHandler = function(event) {
    return function(err) {
      if(event != 'error') {
        self.emit(event, err);
      }
    }
  }

  // Error handler
  var reconnectHandler = function() {
    self.emit('reconnect');
    self.s.store.execute();
  }

  // relay the event
  var relay = function(event) {
    return function(t, server) {
      self.emit(event, t, server);
    }
  }

  // Connect handler
  var connectHandler = function() {
    // Clear out all the current handlers left over
    ["timeout", "error", "close", 'serverOpening', 'serverDescriptionChanged', 'serverHeartbeatStarted',
      'serverHeartbeatSucceeded', 'serverHeartbeatFailed', 'serverClosed', 'topologyOpening',
      'topologyClosed', 'topologyDescriptionChanged'].forEach(function(e) {
      self.s.mongos.removeAllListeners(e);
    });

    // Set up listeners
    self.s.mongos.once('timeout', errorHandler('timeout'));
    self.s.mongos.once('error', errorHandler('error'));
    self.s.mongos.once('close', errorHandler('close'));

    // Set up SDAM listeners
    self.s.mongos.on('serverDescriptionChanged', relay('serverDescriptionChanged'));
    self.s.mongos.on('serverHeartbeatStarted', relay('serverHeartbeatStarted'));
    self.s.mongos.on('serverHeartbeatSucceeded', relay('serverHeartbeatSucceeded'));
    self.s.mongos.on('serverHeartbeatFailed', relay('serverHeartbeatFailed'));
    self.s.mongos.on('serverOpening', relay('serverOpening'));
    self.s.mongos.on('serverClosed', relay('serverClosed'));
    self.s.mongos.on('topologyOpening', relay('topologyOpening'));
    self.s.mongos.on('topologyClosed', relay('topologyClosed'));
    self.s.mongos.on('topologyDescriptionChanged', relay('topologyDescriptionChanged'));

    // Set up serverConfig listeners
    self.s.mongos.on('fullsetup', relay('fullsetup'));

    // Emit open event
    self.emit('open', null, self);

    // Return correctly
    try {
      callback(null, self);
    } catch(err) {
      process.nextTick(function() { throw err; })
    }
  }

  // Set up listeners
  self.s.mongos.once('timeout', connectErrorHandler('timeout'));
  self.s.mongos.once('error', connectErrorHandler('error'));
  self.s.mongos.once('close', connectErrorHandler('close'));
  self.s.mongos.once('connect', connectHandler);
  // Join and leave events
  self.s.mongos.on('joined', relay('joined'));
  self.s.mongos.on('left', relay('left'));

  // Reconnect server
  self.s.mongos.on('reconnect', reconnectHandler);

  // Start connection
  self.s.mongos.connect(_options);
}
```
- example usage
```shell
...
var Db = mongo.Db;
var Server = mongo.Server;
var MongoClient = mongo.MongoClient;
var ReplSetServers = mongo.ReplSetServers;
...
'''

### MongoClient.connect(...)

returns a 'Db' instance

alias origin 'MongoClient.connect(..., function(err, db) { .... })'

origin:
...
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.connections"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>connections ()](#apidoc.element.mongoskin.Mongos.prototype.connections)
- description and source-code
```javascript
connections = function () {
  return this.s.mongos.connections();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.cursor"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>cursor (ns, cmd, options)](#apidoc.element.mongoskin.Mongos.prototype.cursor)
- description and source-code
```javascript
cursor = function (ns, cmd, options) {
  options.disconnectHandler = this.s.store;
  return this.s.mongos.cursor(ns, cmd, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.insert"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>insert (ns, ops, options, callback)](#apidoc.element.mongoskin.Mongos.prototype.insert)
- description and source-code
```javascript
insert = function (ns, ops, options, callback) {
  this.s.mongos.insert(ns, ops, options, function(e, m) {
    callback(e, m)
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.isConnected"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>isConnected ()](#apidoc.element.mongoskin.Mongos.prototype.isConnected)
- description and source-code
```javascript
isConnected = function () {
  return this.s.mongos.isConnected();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.isDestroyed"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>isDestroyed ()](#apidoc.element.mongoskin.Mongos.prototype.isDestroyed)
- description and source-code
```javascript
isDestroyed = function () {
  return this.s.mongos.isDestroyed();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.lastIsMaster"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>lastIsMaster ()](#apidoc.element.mongoskin.Mongos.prototype.lastIsMaster)
- description and source-code
```javascript
lastIsMaster = function () {
  return this.s.mongos.lastIsMaster();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.logout"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>logout ()](#apidoc.element.mongoskin.Mongos.prototype.logout)
- description and source-code
```javascript
logout = function () {
  var args = Array.prototype.slice.call(arguments, 0);
  this.s.mongos.logout.apply(this.s.mongos, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.remove"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>remove (ns, ops, options, callback)](#apidoc.element.mongoskin.Mongos.prototype.remove)
- description and source-code
```javascript
remove = function (ns, ops, options, callback) {
  this.s.mongos.remove(ns, ops, options, callback);
}
```
- example usage
```shell
...
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native

### Removed API from mongoskin 1.3.20
...
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.unref"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>unref ()](#apidoc.element.mongoskin.Mongos.prototype.unref)
- description and source-code
```javascript
unref = function () {
  return this.s.mongos.unref();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Mongos.prototype.update"></a>[function <span class="apidocSignatureSpan">mongoskin.Mongos.prototype.</span>update (ns, ops, options, callback)](#apidoc.element.mongoskin.Mongos.prototype.update)
- description and source-code
```javascript
update = function (ns, ops, options, callback) {
  this.s.mongos.update(ns, ops, options, callback);
}
```
- example usage
```shell
...
### db.gridStore(...)
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native
...
```



# <a name="apidoc.module.mongoskin.ObjectID"></a>[module mongoskin.ObjectID](#apidoc.module.mongoskin.ObjectID)

#### <a name="apidoc.element.mongoskin.ObjectID.ObjectID"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>ObjectID (id)](#apidoc.element.mongoskin.ObjectID.ObjectID)
- description and source-code
```javascript
function ObjectID(id) {
  // Duck-typing to support ObjectId from different npm packages
  if(id instanceof ObjectID) return id;
  if(!(this instanceof ObjectID)) return new ObjectID(id);

  this._bsontype = 'ObjectID';

  // The most common usecase (blank id, new objectId instance)
  if(id == null || typeof id == 'number') {
    // Generate a new id
    this.id = this.generate(id);
    // If we are caching the hex string
    if(ObjectID.cacheHexString) this.__id = this.toString('hex');
    // Return the object
    return;
  }

  // Check if the passed in id is valid
  var valid = ObjectID.isValid(id);

  // Throw an error if it's not a valid setup
  if(!valid && id != null){
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  } else if(valid && typeof id == 'string' && id.length == 24 && hasBufferType) {
    return new ObjectID(new Buffer(id, 'hex'));
  } else if(valid && typeof id == 'string' && id.length == 24) {
    return ObjectID.createFromHexString(id);
  } else if(id != null && id.length === 12) {
    // assume 12 byte string
    this.id = id;
  } else if(id != null && id.toHexString) {
    // Duck-typing to support ObjectId from different npm packages
    return id;
  } else {
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  }

  if(ObjectID.cacheHexString) this.__id = this.toString('hex');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.ObjectId"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.</span>ObjectId (id)](#apidoc.element.mongoskin.ObjectID.ObjectId)
- description and source-code
```javascript
function ObjectID(id) {
  // Duck-typing to support ObjectId from different npm packages
  if(id instanceof ObjectID) return id;
  if(!(this instanceof ObjectID)) return new ObjectID(id);

  this._bsontype = 'ObjectID';

  // The most common usecase (blank id, new objectId instance)
  if(id == null || typeof id == 'number') {
    // Generate a new id
    this.id = this.generate(id);
    // If we are caching the hex string
    if(ObjectID.cacheHexString) this.__id = this.toString('hex');
    // Return the object
    return;
  }

  // Check if the passed in id is valid
  var valid = ObjectID.isValid(id);

  // Throw an error if it's not a valid setup
  if(!valid && id != null){
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  } else if(valid && typeof id == 'string' && id.length == 24 && hasBufferType) {
    return new ObjectID(new Buffer(id, 'hex'));
  } else if(valid && typeof id == 'string' && id.length == 24) {
    return ObjectID.createFromHexString(id);
  } else if(id != null && id.length === 12) {
    // assume 12 byte string
    this.id = id;
  } else if(id != null && id.toHexString) {
    // Duck-typing to support ObjectId from different npm packages
    return id;
  } else {
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  }

  if(ObjectID.cacheHexString) this.__id = this.toString('hex');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.createFromHexString"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.</span>createFromHexString (string)](#apidoc.element.mongoskin.ObjectID.createFromHexString)
- description and source-code
```javascript
function createFromHexString(string) {
  // Throw an error if it's not a valid setup
  if(typeof string === 'undefined' || string != null && string.length != 24) {
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  }

  // Use Buffer.from method if available
  if(hasBufferType) return new ObjectID(new Buffer(string, 'hex'));

  // Calculate lengths
  var array = new _Buffer(12);
  var n = 0;
  var i = 0;

  while (i < 24) {
    array[n++] = decodeLookup[string.charCodeAt(i++)] << 4 | decodeLookup[string.charCodeAt(i++)]
  }

  return new ObjectID(array);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.createFromTime"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.</span>createFromTime (time)](#apidoc.element.mongoskin.ObjectID.createFromTime)
- description and source-code
```javascript
function createFromTime(time) {
  var buffer = new Buffer([0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]);
  // Encode time into first 4 bytes
  buffer[3] = time & 0xff;
  buffer[2] = (time >> 8) & 0xff;
  buffer[1] = (time >> 16) & 0xff;
  buffer[0] = (time >> 24) & 0xff;
  // Return the new objectId
  return new ObjectID(buffer);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.createPk"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.</span>createPk ()](#apidoc.element.mongoskin.ObjectID.createPk)
- description and source-code
```javascript
function createPk() {
  return new ObjectID();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.isValid"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.</span>isValid (id)](#apidoc.element.mongoskin.ObjectID.isValid)
- description and source-code
```javascript
function isValid(id) {
  if(id == null) return false;

  if(typeof id == 'number') {
    return true;
  }

  if(typeof id == 'string') {
    return id.length == 12 || (id.length == 24 && checkForHexRegExp.test(id));
  }

  if(id instanceof ObjectID) {
    return true;
  }

  if(id instanceof _Buffer) {
    return true;
  }

  // Duck-Typing detection of ObjectId like objects
  if(id.toHexString) {
    return id.id.length == 12 || (id.id.length == 24 && checkForHexRegExp.test(id.id));
  }

  return false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.ObjectID.prototype"></a>[module mongoskin.ObjectID.prototype](#apidoc.module.mongoskin.ObjectID.prototype)

#### <a name="apidoc.element.mongoskin.ObjectID.prototype.equals"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>equals (otherId)](#apidoc.element.mongoskin.ObjectID.prototype.equals)
- description and source-code
```javascript
function equals(otherId) {
  var id;

  if(otherId instanceof ObjectID) {
    return this.toString() == otherId.toString();
  } else if(typeof otherId == 'string' && ObjectID.isValid(otherId) && otherId.length == 12 && this.id instanceof _Buffer) {
    return otherId === this.id.toString('binary');
  } else if(typeof otherId == 'string' && ObjectID.isValid(otherId) && otherId.length == 24) {
    return otherId.toLowerCase() === this.toHexString();
  } else if(typeof otherId == 'string' && ObjectID.isValid(otherId) && otherId.length == 12) {
    return otherId === this.id;
  } else if(otherId != null && (otherId instanceof ObjectID || otherId.toHexString)) {
    return otherId.toHexString() === this.toHexString();
  } else {
    return false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.prototype.generate"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>generate (time)](#apidoc.element.mongoskin.ObjectID.prototype.generate)
- description and source-code
```javascript
generate = function (time) {
  if ('number' != typeof time) {
    time = ~~(Date.now()/1000);
  }

  // Use pid
  var pid = (typeof process === 'undefined' ? Math.floor(Math.random() * 100000) : process.pid) % 0xFFFF;
  var inc = this.get_inc();
  // Buffer used
  var buffer = new Buffer(12);
  // Encode time
  buffer[3] = time & 0xff;
  buffer[2] = (time >> 8) & 0xff;
  buffer[1] = (time >> 16) & 0xff;
  buffer[0] = (time >> 24) & 0xff;
  // Encode machine
  buffer[6] = MACHINE_ID & 0xff;
  buffer[5] = (MACHINE_ID >> 8) & 0xff;
  buffer[4] = (MACHINE_ID >> 16) & 0xff;
  // Encode pid
  buffer[8] = pid & 0xff;
  buffer[7] = (pid >> 8) & 0xff;
  // Encode index
  buffer[11] = inc & 0xff;
  buffer[10] = (inc >> 8) & 0xff;
  buffer[9] = (inc >> 16) & 0xff;
  // Return the buffer
  return buffer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.prototype.getInc"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>getInc ()](#apidoc.element.mongoskin.ObjectID.prototype.getInc)
- description and source-code
```javascript
getInc = function () {
  return this.get_inc();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.prototype.getTimestamp"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>getTimestamp ()](#apidoc.element.mongoskin.ObjectID.prototype.getTimestamp)
- description and source-code
```javascript
getTimestamp = function () {
  var timestamp = new Date();
  var time = this.id[3] | this.id[2] << 8 | this.id[1] << 16 | this.id[0] << 24;
  timestamp.setTime(Math.floor(time) * 1000);
  return timestamp;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.prototype.get_inc"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>get_inc ()](#apidoc.element.mongoskin.ObjectID.prototype.get_inc)
- description and source-code
```javascript
get_inc = function () {
  return ObjectID.index = (ObjectID.index + 1) % 0xFFFFFF;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.prototype.inspect"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>inspect (format)](#apidoc.element.mongoskin.ObjectID.prototype.inspect)
- description and source-code
```javascript
inspect = function (format) {
  // Is the id a buffer then use the buffer toString method to return the format
  if(this.id && this.id.copy) {
    return this.id.toString(typeof format === 'string' ? format : 'hex');
  }

  // if(this.buffer )
  return this.toHexString();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.prototype.toHexString"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>toHexString ()](#apidoc.element.mongoskin.ObjectID.prototype.toHexString)
- description and source-code
```javascript
toHexString = function () {
  if(ObjectID.cacheHexString && this.__id) return this.__id;

  var hexString = '';
  if(!this.id || !this.id.length) {
    throw new Error('invalid ObjectId, ObjectId.id must be either a string or a Buffer, but is [' + JSON.stringify(this.id) + ']');
  }

  if(this.id instanceof _Buffer) {
    hexString = convertToHex(this.id);
    if(ObjectID.cacheHexString) this.__id = hexString;
    return hexString;
  }

  for (var i = 0; i < this.id.length; i++) {
    hexString += hexTable[this.id.charCodeAt(i)];
  }

  if(ObjectID.cacheHexString) this.__id = hexString;
  return hexString;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>toJSON ()](#apidoc.element.mongoskin.ObjectID.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.toHexString();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ObjectID.prototype.toString"></a>[function <span class="apidocSignatureSpan">mongoskin.ObjectID.prototype.</span>toString (format)](#apidoc.element.mongoskin.ObjectID.prototype.toString)
- description and source-code
```javascript
toString = function (format) {
  // Is the id a buffer then use the buffer toString method to return the format
  if(this.id && this.id.copy) {
    return this.id.toString(typeof format === 'string' ? format : 'hex');
  }

  // if(this.buffer )
  return this.toHexString();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.ReadPreference"></a>[module mongoskin.ReadPreference](#apidoc.module.mongoskin.ReadPreference)

#### <a name="apidoc.element.mongoskin.ReadPreference.ReadPreference"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>ReadPreference (mode, tags, options)](#apidoc.element.mongoskin.ReadPreference.ReadPreference)
- description and source-code
```javascript
ReadPreference = function (mode, tags, options) {
  if(!(this instanceof ReadPreference)) {
    return new ReadPreference(mode, tags, options);
  }

  this._type = 'ReadPreference';
  this.mode = mode;
  this.tags = tags;
  this.options =  options;

  // If no tags were passed in
  if(tags && typeof tags == 'object' && !Array.isArray(tags)) {
    if(tags.maxStalenessSeconds) {
      this.options = tags;
      this.tags = null;
    }
  }

  // Add the maxStalenessSeconds value to the read Preference
  if(this.options && this.options.maxStalenessSeconds) {
    this.maxStalenessSeconds = this.options.maxStalenessSeconds;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReadPreference.isValid"></a>[function <span class="apidocSignatureSpan">mongoskin.ReadPreference.</span>isValid (_mode)](#apidoc.element.mongoskin.ReadPreference.isValid)
- description and source-code
```javascript
isValid = function (_mode) {
  return (_mode == ReadPreference.PRIMARY || _mode == ReadPreference.PRIMARY_PREFERRED
    || _mode == ReadPreference.SECONDARY || _mode == ReadPreference.SECONDARY_PREFERRED
    || _mode == ReadPreference.NEAREST
    || _mode == true || _mode == false || _mode == null);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.ReadPreference.prototype"></a>[module mongoskin.ReadPreference.prototype](#apidoc.module.mongoskin.ReadPreference.prototype)

#### <a name="apidoc.element.mongoskin.ReadPreference.prototype.isValid"></a>[function <span class="apidocSignatureSpan">mongoskin.ReadPreference.prototype.</span>isValid (mode)](#apidoc.element.mongoskin.ReadPreference.prototype.isValid)
- description and source-code
```javascript
isValid = function (mode) {
  var _mode = typeof mode == 'string' ? mode : this.mode;
  return ReadPreference.isValid(_mode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReadPreference.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.ReadPreference.prototype.</span>toJSON ()](#apidoc.element.mongoskin.ReadPreference.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.toObject();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReadPreference.prototype.toObject"></a>[function <span class="apidocSignatureSpan">mongoskin.ReadPreference.prototype.</span>toObject ()](#apidoc.element.mongoskin.ReadPreference.prototype.toObject)
- description and source-code
```javascript
toObject = function () {
  var object = {mode:this.mode};

  if(this.tags != null) {
    object['tags'] = this.tags;
  }

  if(this.maxStalenessSeconds) {
    object['maxStalenessSeconds'] = this.maxStalenessSeconds;
  }

  return object;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.ReplSet"></a>[module mongoskin.ReplSet](#apidoc.module.mongoskin.ReplSet)

#### <a name="apidoc.element.mongoskin.ReplSet.ReplSet"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>ReplSet (servers, options)](#apidoc.element.mongoskin.ReplSet.ReplSet)
- description and source-code
```javascript
ReplSet = function (servers, options) {
  if(!(this instanceof ReplSet)) return new ReplSet(servers, options);
  options = options || {};
  var self = this;
  // Set up event emitter
  EventEmitter.call(this);

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Ensure all the instances are Server
  for(var i = 0; i < servers.length; i++) {
    if(!(servers[i] instanceof Server)) {
      throw MongoError.create({message: "all seed list instances must be of the Server type", driver:true});
    }
  }

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Build seed list
  var seedlist = servers.map(function(x) {
    return {host: x.host, port: x.port}
  });

  // Clone options
  var clonedOptions = mergeOptions({}, {
    disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: false,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Client info
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create the ReplSet
  var replset = new CReplSet(seedlist, clonedOptions);

  // Listen to reconnect event
  replset.on('reconnect', function() {
    self.emit('reconnect');
    store.execute();
  });

  // Internal state
  this.s = {
    // Replicaset
    replset: replset
    // Server capabilities
    , sCapabilities: null
    // Debug tag
    , tag: options.tag
    // Store options
    , storeOptions: storeOptions
    // Cloned options
    , clonedOptions: clonedOptions
    // Store
    , store: store
    // Options
    , options: options
  }

  // Debug
  if(clonedOptions.debug) {
    // Last ismaster
    Object.defineProperty(this, 'replset', {
      enumerable:true, get: function() { return replset; }
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.super_"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.</span>super_ ()](#apidoc.element.mongoskin.ReplSet.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.ReplSet.define"></a>[module mongoskin.ReplSet.define](#apidoc.module.mongoskin.ReplSet.define)

#### <a name="apidoc.element.mongoskin.ReplSet.define.object"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.define.</span>object (servers, options)](#apidoc.element.mongoskin.ReplSet.define.object)
- description and source-code
```javascript
object = function (servers, options) {
  if(!(this instanceof ReplSet)) return new ReplSet(servers, options);
  options = options || {};
  var self = this;
  // Set up event emitter
  EventEmitter.call(this);

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Ensure all the instances are Server
  for(var i = 0; i < servers.length; i++) {
    if(!(servers[i] instanceof Server)) {
      throw MongoError.create({message: "all seed list instances must be of the Server type", driver:true});
    }
  }

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Build seed list
  var seedlist = servers.map(function(x) {
    return {host: x.host, port: x.port}
  });

  // Clone options
  var clonedOptions = mergeOptions({}, {
    disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: false,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Client info
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create the ReplSet
  var replset = new CReplSet(seedlist, clonedOptions);

  // Listen to reconnect event
  replset.on('reconnect', function() {
    self.emit('reconnect');
    store.execute();
  });

  // Internal state
  this.s = {
    // Replicaset
    replset: replset
    // Server capabilities
    , sCapabilities: null
    // Debug tag
    , tag: options.tag
    // Store options
    , storeOptions: storeOptions
    // Cloned options
    , clonedOptions: clonedOptions
    // Store
    , store: store
    // Options
    , options: options
  }

  // Debug
  if(clonedOptions.debug) {
    // Last ismaster
    Object.defineProperty(this, 'replset', {
      enumerable:true, get: function() { return replset; }
    });
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.ReplSet.prototype"></a>[module mongoskin.ReplSet.prototype](#apidoc.module.mongoskin.ReplSet.prototype)

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.auth"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>auth ()](#apidoc.element.mongoskin.ReplSet.prototype.auth)
- description and source-code
```javascript
auth = function () {
  var args = Array.prototype.slice.call(arguments, 0);
  this.s.replset.auth.apply(this.s.replset, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.capabilities"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>capabilities ()](#apidoc.element.mongoskin.ReplSet.prototype.capabilities)
- description and source-code
```javascript
capabilities = function () {
  if(this.s.sCapabilities) return this.s.sCapabilities;
  if(this.s.replset.lastIsMaster() == null) return null;
  this.s.sCapabilities = new ServerCapabilities(this.s.replset.lastIsMaster());
  return this.s.sCapabilities;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>close (forceClosed)](#apidoc.element.mongoskin.ReplSet.prototype.close)
- description and source-code
```javascript
close = function (forceClosed) {
  var self = this;
  // Call destroy on the topology
  this.s.replset.destroy({
    force: typeof forceClosed == 'boolean' ? forceClosed : false,
  });
  // We need to wash out all stored processes
  if(forceClosed == true) {
    this.s.storeOptions.force = forceClosed;
    this.s.store.flush();
  }

  var events = ['timeout', 'error', 'close', 'joined', 'left'];
  events.forEach(function(e) {
    self.removeAllListeners(e);
  });
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.command"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>command (ns, cmd, options, callback)](#apidoc.element.mongoskin.ReplSet.prototype.command)
- description and source-code
```javascript
command = function (ns, cmd, options, callback) {
  this.s.replset.command(ns, cmd, getReadPreference(options), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.connect"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>connect (db, _options, callback)](#apidoc.element.mongoskin.ReplSet.prototype.connect)
- description and source-code
```javascript
connect = function (db, _options, callback) {
  var self = this;
  if('function' === typeof _options) callback = _options, _options = {};
  if(_options == null) _options = {};
  if(!('function' === typeof callback)) callback = null;
  self.s.options = _options;

  // Update bufferMaxEntries
  self.s.storeOptions.bufferMaxEntries = db.bufferMaxEntries;

  // Actual handler
  var errorHandler = function(event) {
    return function(err) {
      if(event != 'error') {
        self.emit(event, err);
      }
    }
  }

  // Connect handler
  var connectHandler = function() {
    // Clear out all the current handlers left over
    ["timeout", "error", "close", 'serverOpening', 'serverDescriptionChanged', 'serverHeartbeatStarted',
      'serverHeartbeatSucceeded', 'serverHeartbeatFailed', 'serverClosed', 'topologyOpening',
      'topologyClosed', 'topologyDescriptionChanged'].forEach(function(e) {
      self.s.replset.removeAllListeners(e);
    });

    // Set up listeners
    self.s.replset.once('timeout', errorHandler('timeout'));
    self.s.replset.once('error', errorHandler('error'));
    self.s.replset.once('close', errorHandler('close'));

    // relay the event
    var relay = function(event) {
      return function(t, server) {
        self.emit(event, t, server);
      }
    }

    // Replset events relay
    var replsetRelay = function(event) {
      return function(t, server) {
        self.emit(event, t, server.lastIsMaster(), server);
      }
    }

    // Relay ha
    var relayHa = function(t, state) {
      self.emit('ha', t, state);

      if(t == 'start') {
        self.emit('ha_connect', t, state);
      } else if(t == 'end') {
        self.emit('ha_ismaster', t, state);
      }
    }

    // Set up serverConfig listeners
    self.s.replset.on('joined', replsetRelay('joined'));
    self.s.replset.on('left', relay('left'));
    self.s.replset.on('ping', relay('ping'));
    self.s.replset.on('ha', relayHa);

    // Set up SDAM listeners
    self.s.replset.on('serverDescriptionChanged', relay('serverDescriptionChanged'));
    self.s.replset.on('serverHeartbeatStarted', relay('serverHeartbeatStarted'));
    self.s.replset.on('serverHeartbeatSucceeded', relay('serverHeartbeatSucceeded'));
    self.s.replset.on('serverHeartbeatFailed', relay('serverHeartbeatFailed'));
    self.s.replset.on('serverOpening', relay('serverOpening'));
    self.s.replset.on('serverClosed', relay('serverClosed'));
    self.s.replset.on('topologyOpening', relay('topologyOpening'));
    self.s.replset.on('topologyClosed', relay('topologyClosed'));
    self.s.replset.on('topologyDescriptionChanged', relay('topologyDescriptionChanged'));

    self.s.replset.on('fullsetup', function() {
      self.emit('fullsetup', null, self);
    });

    self.s.replset.on('all', function() {
      self.emit('all', null, self);
    });

    // Emit open event
    self.emit('open', null, self);

    // Return correctly
    try {
      callback(null, self);
    } catch(err) {
      process.nextTick(function() { throw err; })
    }
  }

  // Error handler
  var connectErrorHandler = function() {
    return function(err) {
      ['timeout', 'error', 'close'].forEach(function(e) {
        self.s.replset.removeListener(e, connectErrorHandler);
      });

      self.s.replset.removeListener('connect', connectErrorHandler);
      // Destroy the replset
      self.s.replset.destroy();

      // Try to callback
      try {
        callback(err);
      } catch(err) {
        if(!self.s.replset.isConnected())
          process.nextTick(function() { throw err; })
      }
    }
  }

  // Set up listeners
  self.s.replset.once('timeout', connectErrorHandler('timeout'));
  self.s.replset.once('error', connectErrorHandler('error'));
  self.s.replset.once('close', connectErrorHandler('close'));
  self.s.replset.once('connect', connectHandler);

  // Start connection
  self.s.replset.connect(_options);
}
```
- example usage
```shell
...
var Db = mongo.Db;
var Server = mongo.Server;
var MongoClient = mongo.MongoClient;
var ReplSetServers = mongo.ReplSetServers;
...
'''

### MongoClient.connect(...)

returns a 'Db' instance

alias origin 'MongoClient.connect(..., function(err, db) { .... })'

origin:
...
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.connections"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>connections ()](#apidoc.element.mongoskin.ReplSet.prototype.connections)
- description and source-code
```javascript
connections = function () {
  return this.s.replset.connections();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.cursor"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>cursor (ns, cmd, options)](#apidoc.element.mongoskin.ReplSet.prototype.cursor)
- description and source-code
```javascript
cursor = function (ns, cmd, options) {
  options = translateReadPreference(options);
  options.disconnectHandler = this.s.store;
  return this.s.replset.cursor(ns, cmd, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.insert"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>insert (ns, ops, options, callback)](#apidoc.element.mongoskin.ReplSet.prototype.insert)
- description and source-code
```javascript
insert = function (ns, ops, options, callback) {
  this.s.replset.insert(ns, ops, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.isConnected"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>isConnected (options)](#apidoc.element.mongoskin.ReplSet.prototype.isConnected)
- description and source-code
```javascript
isConnected = function (options) {
  options = options || {};

  // If we passed in a readPreference, translate to
  // a CoreReadPreference instance
  if(options.readPreference) {
    options.readPreference = translateReadPreference(options.readPreference);
  }

  return this.s.replset.isConnected(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.isDestroyed"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>isDestroyed ()](#apidoc.element.mongoskin.ReplSet.prototype.isDestroyed)
- description and source-code
```javascript
isDestroyed = function () {
  return this.s.replset.isDestroyed();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.lastIsMaster"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>lastIsMaster ()](#apidoc.element.mongoskin.ReplSet.prototype.lastIsMaster)
- description and source-code
```javascript
lastIsMaster = function () {
  return this.s.replset.lastIsMaster();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.logout"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>logout ()](#apidoc.element.mongoskin.ReplSet.prototype.logout)
- description and source-code
```javascript
logout = function () {
  var args = Array.prototype.slice.call(arguments, 0);
  this.s.replset.logout.apply(this.s.replset, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.remove"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>remove (ns, ops, options, callback)](#apidoc.element.mongoskin.ReplSet.prototype.remove)
- description and source-code
```javascript
remove = function (ns, ops, options, callback) {
  this.s.replset.remove(ns, ops, options, callback);
}
```
- example usage
```shell
...
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native

### Removed API from mongoskin 1.3.20
...
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.unref"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>unref ()](#apidoc.element.mongoskin.ReplSet.prototype.unref)
- description and source-code
```javascript
unref = function () {
  return this.s.replset.unref();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.ReplSet.prototype.update"></a>[function <span class="apidocSignatureSpan">mongoskin.ReplSet.prototype.</span>update (ns, ops, options, callback)](#apidoc.element.mongoskin.ReplSet.prototype.update)
- description and source-code
```javascript
update = function (ns, ops, options, callback) {
  this.s.replset.update(ns, ops, options, callback);
}
```
- example usage
```shell
...
### db.gridStore(...)
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native
...
```



# <a name="apidoc.module.mongoskin.Server"></a>[module mongoskin.Server](#apidoc.module.mongoskin.Server)

#### <a name="apidoc.element.mongoskin.Server.Server"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Server (host, port, options)](#apidoc.element.mongoskin.Server.Server)
- description and source-code
```javascript
Server = function (host, port, options) {
  options = options || {};
  if(!(this instanceof Server)) return new Server(host, port, options);
  EventEmitter.call(this);
  var self = this;

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Detect if we have a socket connection
  if(host.indexOf('\/') != -1) {
    if(port != null && typeof port == 'object') {
      options = port;
      port = null;
    }
  } else if(port == null) {
    throw MongoError.create({message: 'port must be specified', driver:true});
  }

  // Get the reconnect option
  var reconnect = typeof options.auto_reconnect == 'boolean' ? options.auto_reconnect : true;
  reconnect = typeof options.autoReconnect == 'boolean' ? options.autoReconnect : reconnect;

  // Clone options
  var clonedOptions = mergeOptions({}, {
    host: host, port: port, disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: reconnect,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Build default client information
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create an instance of a server instance from mongodb-core
  var server = new CServer(clonedOptions);

  // Define the internal properties
  this.s = {
    // Create an instance of a server instance from mongodb-core
      server: server
    // Server capabilities
    , sCapabilities: null
    // Cloned options
    , clonedOptions: clonedOptions
    // Reconnect
    , reconnect: clonedOptions.reconnect
    // Emit error
    , emitError: clonedOptions.emitError
    // Pool size
    , poolSize: clonedOptions.size
    // Store Options
    , storeOptions: storeOptions
    // Store
    , store: store
    // Host
    , host: host
    // Port
    , port: port
    // Options
    , options: options
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.super_"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.</span>super_ ()](#apidoc.element.mongoskin.Server.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Server.define"></a>[module mongoskin.Server.define](#apidoc.module.mongoskin.Server.define)

#### <a name="apidoc.element.mongoskin.Server.define.object"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.define.</span>object (host, port, options)](#apidoc.element.mongoskin.Server.define.object)
- description and source-code
```javascript
object = function (host, port, options) {
  options = options || {};
  if(!(this instanceof Server)) return new Server(host, port, options);
  EventEmitter.call(this);
  var self = this;

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Detect if we have a socket connection
  if(host.indexOf('\/') != -1) {
    if(port != null && typeof port == 'object') {
      options = port;
      port = null;
    }
  } else if(port == null) {
    throw MongoError.create({message: 'port must be specified', driver:true});
  }

  // Get the reconnect option
  var reconnect = typeof options.auto_reconnect == 'boolean' ? options.auto_reconnect : true;
  reconnect = typeof options.autoReconnect == 'boolean' ? options.autoReconnect : reconnect;

  // Clone options
  var clonedOptions = mergeOptions({}, {
    host: host, port: port, disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: reconnect,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Build default client information
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create an instance of a server instance from mongodb-core
  var server = new CServer(clonedOptions);

  // Define the internal properties
  this.s = {
    // Create an instance of a server instance from mongodb-core
      server: server
    // Server capabilities
    , sCapabilities: null
    // Cloned options
    , clonedOptions: clonedOptions
    // Reconnect
    , reconnect: clonedOptions.reconnect
    // Emit error
    , emitError: clonedOptions.emitError
    // Pool size
    , poolSize: clonedOptions.size
    // Store Options
    , storeOptions: storeOptions
    // Store
    , store: store
    // Host
    , host: host
    // Port
    , port: port
    // Options
    , options: options
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Server.prototype"></a>[module mongoskin.Server.prototype](#apidoc.module.mongoskin.Server.prototype)

#### <a name="apidoc.element.mongoskin.Server.prototype.auth"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>auth ()](#apidoc.element.mongoskin.Server.prototype.auth)
- description and source-code
```javascript
auth = function () {
  var args = Array.prototype.slice.call(arguments, 0);
  this.s.server.auth.apply(this.s.server, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.prototype.capabilities"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>capabilities ()](#apidoc.element.mongoskin.Server.prototype.capabilities)
- description and source-code
```javascript
capabilities = function () {
  if(this.s.sCapabilities) return this.s.sCapabilities;
  if(this.s.server.lastIsMaster() == null) return null;
  this.s.sCapabilities = new ServerCapabilities(this.s.server.lastIsMaster());
  return this.s.sCapabilities;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>close (forceClosed)](#apidoc.element.mongoskin.Server.prototype.close)
- description and source-code
```javascript
close = function (forceClosed) {
  this.s.server.destroy();
  // We need to wash out all stored processes
  if(forceClosed == true) {
    this.s.storeOptions.force = forceClosed;
    this.s.store.flush();
  }
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.Server.prototype.command"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>command (ns, cmd, options, callback)](#apidoc.element.mongoskin.Server.prototype.command)
- description and source-code
```javascript
command = function (ns, cmd, options, callback) {
  this.s.server.command(ns, cmd, getReadPreference(options), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.prototype.connect"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>connect (db, _options, callback)](#apidoc.element.mongoskin.Server.prototype.connect)
- description and source-code
```javascript
connect = function (db, _options, callback) {
  var self = this;
  if('function' === typeof _options) callback = _options, _options = {};
  if(_options == null) _options = {};
  if(!('function' === typeof callback)) callback = null;
  self.s.options = _options;

  // Update bufferMaxEntries
  self.s.storeOptions.bufferMaxEntries = db.bufferMaxEntries;

  // Error handler
  var connectErrorHandler = function() {
    return function(err) {
      // Remove all event handlers
      var events = ['timeout', 'error', 'close'];
      events.forEach(function(e) {
        self.s.server.removeListener(e, connectHandlers[e]);
      });

      self.s.server.removeListener('connect', connectErrorHandler);

      // Try to callback
      try {
        callback(err);
      } catch(err) {
        process.nextTick(function() { throw err; })
      }
    }
  }

  // Actual handler
  var errorHandler = function(event) {
    return function(err) {
      if(event != 'error') {
        self.emit(event, err);
      }
    }
  }

  // Error handler
  var reconnectHandler = function() {
    self.emit('reconnect', self);
    self.s.store.execute();
  }

  // Reconnect failed
  var reconnectFailedHandler = function(err) {
    self.emit('reconnectFailed', err);
    self.s.store.flush(err);
  }

  // Destroy called on topology, perform cleanup
  var destroyHandler = function() {
    self.s.store.flush();
  }

  // Connect handler
  var connectHandler = function() {
    // Clear out all the current handlers left over
    ["timeout", "error", "close", 'serverOpening', 'serverDescriptionChanged', 'serverHeartbeatStarted',
      'serverHeartbeatSucceeded', 'serverHeartbeatFailed', 'serverClosed', 'topologyOpening',
      'topologyClosed', 'topologyDescriptionChanged'].forEach(function(e) {
      self.s.server.removeAllListeners(e);
    });

    // Set up listeners
    self.s.server.on('timeout', errorHandler('timeout'));
    self.s.server.once('error', errorHandler('error'));
    self.s.server.on('close', errorHandler('close'));
    // Only called on destroy
    self.s.server.on('destroy', destroyHandler);

    // relay the event
    var relay = function(event) {
      return function(t, server) {
        self.emit(event, t, server);
      }
    }

    // Set up SDAM listeners
    self.s.server.on('serverDescriptionChanged', relay('serverDescriptionChanged'));
    self.s.server.on('serverHeartbeatStarted', relay('serverHeartbeatStarted'));
    self.s.server.on('serverHeartbeatSucceeded', relay('serverHeartbeatSucceeded'));
    self.s.server.on('serverHeartbeatFailed', relay('serverHeartbeatFailed'));
    self.s.server.on('serverOpening', relay('serverOpening'));
    self.s.server.on('serverClosed', relay('serverClosed'));
    self.s.server.on('topologyOpening', relay('topologyOpening'));
    self.s.server.on('topologyClosed', relay('topologyClosed'));
    self.s.server.on('topologyDescriptionChanged', relay('topologyDescriptionChanged'));
    self.s.server.on('attemptReconnect', relay('attemptReconnect'));
    self.s.server.on('monitoring', relay('monitoring'));

    // Emit open event
    self.emit('open', null, self);

    // Return correctly
    try {
      callback(null, self);
    } catch(err) {
      console.log(err.stack)
      process.nextTick(function() { throw err; })
    }
  }

  // Set up listeners
  var connectHandlers = {
    timeout: connectErrorHandler('timeout'),
    error: connectErrorHandler('error'),
    close: connectErrorHandler('close')
  };

  // Add the event handlers
  self.s.server.once('timeout', connectHandlers.timeout);
  self.s.server.once('error', connectHandlers.error);
  self.s.server.once('close', connectHandlers.close);
  self.s.server.once('connect', connectHandler);
  // Reconnect server
  self.s.server.on('reconnect', reconnectHandler);
  self.s.server.on('reconnectFailed', reconnectFailedHandler);

  // Start connection
  self.s.server.connect(_options);
}
```
- example usage
```shell
...
var Db = mongo.Db;
var Server = mongo.Server;
var MongoClient = mongo.MongoClient;
var ReplSetServers = mongo.ReplSetServers;
...
'''

### MongoClient.connect(...)

returns a 'Db' instance

alias origin 'MongoClient.connect(..., function(err, db) { .... })'

origin:
...
```

#### <a name="apidoc.element.mongoskin.Server.prototype.connections"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>connections ()](#apidoc.element.mongoskin.Server.prototype.connections)
- description and source-code
```javascript
connections = function () {
  return this.s.server.connections();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.prototype.cursor"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>cursor (ns, cmd, options)](#apidoc.element.mongoskin.Server.prototype.cursor)
- description and source-code
```javascript
cursor = function (ns, cmd, options) {
  options.disconnectHandler = this.s.store;
  return this.s.server.cursor(ns, cmd, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.prototype.insert"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>insert (ns, ops, options, callback)](#apidoc.element.mongoskin.Server.prototype.insert)
- description and source-code
```javascript
insert = function (ns, ops, options, callback) {
  this.s.server.insert(ns, ops, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.prototype.isConnected"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>isConnected ()](#apidoc.element.mongoskin.Server.prototype.isConnected)
- description and source-code
```javascript
isConnected = function () {
  return this.s.server.isConnected();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.prototype.isDestroyed"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>isDestroyed ()](#apidoc.element.mongoskin.Server.prototype.isDestroyed)
- description and source-code
```javascript
isDestroyed = function () {
  return this.s.server.isDestroyed();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.prototype.lastIsMaster"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>lastIsMaster ()](#apidoc.element.mongoskin.Server.prototype.lastIsMaster)
- description and source-code
```javascript
lastIsMaster = function () {
  return this.s.server.lastIsMaster();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.prototype.logout"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>logout ()](#apidoc.element.mongoskin.Server.prototype.logout)
- description and source-code
```javascript
logout = function () {
  var args = Array.prototype.slice.call(arguments, 0);
  this.s.server.logout.apply(this.s.server, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.prototype.remove"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>remove (ns, ops, options, callback)](#apidoc.element.mongoskin.Server.prototype.remove)
- description and source-code
```javascript
remove = function (ns, ops, options, callback) {
  this.s.server.remove(ns, ops, options, callback);
}
```
- example usage
```shell
...
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native

### Removed API from mongoskin 1.3.20
...
```

#### <a name="apidoc.element.mongoskin.Server.prototype.unref"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>unref ()](#apidoc.element.mongoskin.Server.prototype.unref)
- description and source-code
```javascript
unref = function () {
  this.s.server.unref();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Server.prototype.update"></a>[function <span class="apidocSignatureSpan">mongoskin.Server.prototype.</span>update (ns, ops, options, callback)](#apidoc.element.mongoskin.Server.prototype.update)
- description and source-code
```javascript
update = function (ns, ops, options, callback) {
  this.s.server.update(ns, ops, options, callback);
}
```
- example usage
```shell
...
### db.gridStore(...)
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native
...
```



# <a name="apidoc.module.mongoskin.Symbol"></a>[module mongoskin.Symbol](#apidoc.module.mongoskin.Symbol)

#### <a name="apidoc.element.mongoskin.Symbol.Symbol"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Symbol (value)](#apidoc.element.mongoskin.Symbol.Symbol)
- description and source-code
```javascript
function Symbol(value) {
  if(!(this instanceof Symbol)) return new Symbol(value);
  this._bsontype = 'Symbol';
  this.value = value;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Symbol.prototype"></a>[module mongoskin.Symbol.prototype](#apidoc.module.mongoskin.Symbol.prototype)

#### <a name="apidoc.element.mongoskin.Symbol.prototype.inspect"></a>[function <span class="apidocSignatureSpan">mongoskin.Symbol.prototype.</span>inspect ()](#apidoc.element.mongoskin.Symbol.prototype.inspect)
- description and source-code
```javascript
inspect = function () {
  return this.value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Symbol.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.Symbol.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Symbol.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Symbol.prototype.toString"></a>[function <span class="apidocSignatureSpan">mongoskin.Symbol.prototype.</span>toString ()](#apidoc.element.mongoskin.Symbol.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return this.value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Symbol.prototype.valueOf"></a>[function <span class="apidocSignatureSpan">mongoskin.Symbol.prototype.</span>valueOf ()](#apidoc.element.mongoskin.Symbol.prototype.valueOf)
- description and source-code
```javascript
valueOf = function () {
  return this.value;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Timestamp"></a>[module mongoskin.Timestamp](#apidoc.module.mongoskin.Timestamp)

#### <a name="apidoc.element.mongoskin.Timestamp.Timestamp"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>Timestamp (low, high)](#apidoc.element.mongoskin.Timestamp.Timestamp)
- description and source-code
```javascript
function Timestamp(low, high) {
  if(!(this instanceof Timestamp)) return new Timestamp(low, high);
  this._bsontype = 'Timestamp';
<span class="apidocCodeCommentSpan">  /**
   * @type {number}
   * @ignore
   */
</span>  this.low_ = low | 0;  // force into 32 signed bits.

  /**
   * @type {number}
   * @ignore
   */
  this.high_ = high | 0;  // force into 32 signed bits.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.fromBits"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>fromBits (lowBits, highBits)](#apidoc.element.mongoskin.Timestamp.fromBits)
- description and source-code
```javascript
fromBits = function (lowBits, highBits) {
  return new Timestamp(lowBits, highBits);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.fromInt"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>fromInt (value)](#apidoc.element.mongoskin.Timestamp.fromInt)
- description and source-code
```javascript
fromInt = function (value) {
  if (-128 <= value && value < 128) {
    var cachedObj = Timestamp.INT_CACHE_[value];
    if (cachedObj) {
      return cachedObj;
    }
  }

  var obj = new Timestamp(value | 0, value < 0 ? -1 : 0);
  if (-128 <= value && value < 128) {
    Timestamp.INT_CACHE_[value] = obj;
  }
  return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.fromNumber"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>fromNumber (value)](#apidoc.element.mongoskin.Timestamp.fromNumber)
- description and source-code
```javascript
fromNumber = function (value) {
  if (isNaN(value) || !isFinite(value)) {
    return Timestamp.ZERO;
  } else if (value <= -Timestamp.TWO_PWR_63_DBL_) {
    return Timestamp.MIN_VALUE;
  } else if (value + 1 >= Timestamp.TWO_PWR_63_DBL_) {
    return Timestamp.MAX_VALUE;
  } else if (value < 0) {
    return Timestamp.fromNumber(-value).negate();
  } else {
    return new Timestamp(
               (value % Timestamp.TWO_PWR_32_DBL_) | 0,
               (value / Timestamp.TWO_PWR_32_DBL_) | 0);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.fromString"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.</span>fromString (str, opt_radix)](#apidoc.element.mongoskin.Timestamp.fromString)
- description and source-code
```javascript
fromString = function (str, opt_radix) {
  if (str.length == 0) {
    throw Error('number format error: empty string');
  }

  var radix = opt_radix || 10;
  if (radix < 2 || 36 < radix) {
    throw Error('radix out of range: ' + radix);
  }

  if (str.charAt(0) == '-') {
    return Timestamp.fromString(str.substring(1), radix).negate();
  } else if (str.indexOf('-') >= 0) {
    throw Error('number format error: interior "-" character: ' + str);
  }

  // Do several (8) digits each time through the loop, so as to
  // minimize the calls to the very expensive emulated div.
  var radixToPower = Timestamp.fromNumber(Math.pow(radix, 8));

  var result = Timestamp.ZERO;
  for (var i = 0; i < str.length; i += 8) {
    var size = Math.min(8, str.length - i);
    var value = parseInt(str.substring(i, i + size), radix);
    if (size < 8) {
      var power = Timestamp.fromNumber(Math.pow(radix, size));
      result = result.multiply(power).add(Timestamp.fromNumber(value));
    } else {
      result = result.multiply(radixToPower);
      result = result.add(Timestamp.fromNumber(value));
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.Timestamp.prototype"></a>[module mongoskin.Timestamp.prototype](#apidoc.module.mongoskin.Timestamp.prototype)

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.add"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>add (other)](#apidoc.element.mongoskin.Timestamp.prototype.add)
- description and source-code
```javascript
add = function (other) {
  // Divide each number into 4 chunks of 16 bits, and then sum the chunks.

  var a48 = this.high_ >>> 16;
  var a32 = this.high_ & 0xFFFF;
  var a16 = this.low_ >>> 16;
  var a00 = this.low_ & 0xFFFF;

  var b48 = other.high_ >>> 16;
  var b32 = other.high_ & 0xFFFF;
  var b16 = other.low_ >>> 16;
  var b00 = other.low_ & 0xFFFF;

  var c48 = 0, c32 = 0, c16 = 0, c00 = 0;
  c00 += a00 + b00;
  c16 += c00 >>> 16;
  c00 &= 0xFFFF;
  c16 += a16 + b16;
  c32 += c16 >>> 16;
  c16 &= 0xFFFF;
  c32 += a32 + b32;
  c48 += c32 >>> 16;
  c32 &= 0xFFFF;
  c48 += a48 + b48;
  c48 &= 0xFFFF;
  return Timestamp.fromBits((c16 << 16) | c00, (c48 << 16) | c32);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.and"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>and (other)](#apidoc.element.mongoskin.Timestamp.prototype.and)
- description and source-code
```javascript
and = function (other) {
  return Timestamp.fromBits(this.low_ & other.low_, this.high_ & other.high_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.compare"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>compare (other)](#apidoc.element.mongoskin.Timestamp.prototype.compare)
- description and source-code
```javascript
compare = function (other) {
  if (this.equals(other)) {
    return 0;
  }

  var thisNeg = this.isNegative();
  var otherNeg = other.isNegative();
  if (thisNeg && !otherNeg) {
    return -1;
  }
  if (!thisNeg && otherNeg) {
    return 1;
  }

  // at this point, the signs are the same, so subtraction will not overflow
  if (this.subtract(other).isNegative()) {
    return -1;
  } else {
    return 1;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.div"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>div (other)](#apidoc.element.mongoskin.Timestamp.prototype.div)
- description and source-code
```javascript
div = function (other) {
  if (other.isZero()) {
    throw Error('division by zero');
  } else if (this.isZero()) {
    return Timestamp.ZERO;
  }

  if (this.equals(Timestamp.MIN_VALUE)) {
    if (other.equals(Timestamp.ONE) ||
        other.equals(Timestamp.NEG_ONE)) {
      return Timestamp.MIN_VALUE;  // recall that -MIN_VALUE == MIN_VALUE
    } else if (other.equals(Timestamp.MIN_VALUE)) {
      return Timestamp.ONE;
    } else {
      // At this point, we have |other| >= 2, so |this/other| < |MIN_VALUE|.
      var halfThis = this.shiftRight(1);
      var approx = halfThis.div(other).shiftLeft(1);
      if (approx.equals(Timestamp.ZERO)) {
        return other.isNegative() ? Timestamp.ONE : Timestamp.NEG_ONE;
      } else {
        var rem = this.subtract(other.multiply(approx));
        var result = approx.add(rem.div(other));
        return result;
      }
    }
  } else if (other.equals(Timestamp.MIN_VALUE)) {
    return Timestamp.ZERO;
  }

  if (this.isNegative()) {
    if (other.isNegative()) {
      return this.negate().div(other.negate());
    } else {
      return this.negate().div(other).negate();
    }
  } else if (other.isNegative()) {
    return this.div(other.negate()).negate();
  }

  // Repeat the following until the remainder is less than other:  find a
  // floating-point that approximates remainder / other *from below*, add this
  // into the result, and subtract it from the remainder.  It is critical that
  // the approximate value is less than or equal to the real value so that the
  // remainder never becomes negative.
  var res = Timestamp.ZERO;
  var rem = this;
  while (rem.greaterThanOrEqual(other)) {
    // Approximate the result of division. This may be a little greater or
    // smaller than the actual value.
    var approx = Math.max(1, Math.floor(rem.toNumber() / other.toNumber()));

    // We will tweak the approximate result by changing it in the 48-th digit or
    // the smallest non-fractional digit, whichever is larger.
    var log2 = Math.ceil(Math.log(approx) / Math.LN2);
    var delta = (log2 <= 48) ? 1 : Math.pow(2, log2 - 48);

    // Decrease the approximation until it is smaller than the remainder.  Note
    // that if it is too large, the product overflows and is negative.
    var approxRes = Timestamp.fromNumber(approx);
    var approxRem = approxRes.multiply(other);
    while (approxRem.isNegative() || approxRem.greaterThan(rem)) {
      approx -= delta;
      approxRes = Timestamp.fromNumber(approx);
      approxRem = approxRes.multiply(other);
    }

    // We know the answer can't be zero... and actually, zero would cause
    // infinite recursion since we would make no progress.
    if (approxRes.isZero()) {
      approxRes = Timestamp.ONE;
    }

    res = res.add(approxRes);
    rem = rem.subtract(approxRem);
  }
  return res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.equals"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>equals (other)](#apidoc.element.mongoskin.Timestamp.prototype.equals)
- description and source-code
```javascript
equals = function (other) {
  return (this.high_ == other.high_) && (this.low_ == other.low_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.getHighBits"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>getHighBits ()](#apidoc.element.mongoskin.Timestamp.prototype.getHighBits)
- description and source-code
```javascript
getHighBits = function () {
  return this.high_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.getLowBits"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>getLowBits ()](#apidoc.element.mongoskin.Timestamp.prototype.getLowBits)
- description and source-code
```javascript
getLowBits = function () {
  return this.low_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.getLowBitsUnsigned"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>getLowBitsUnsigned ()](#apidoc.element.mongoskin.Timestamp.prototype.getLowBitsUnsigned)
- description and source-code
```javascript
getLowBitsUnsigned = function () {
  return (this.low_ >= 0) ?
      this.low_ : Timestamp.TWO_PWR_32_DBL_ + this.low_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.getNumBitsAbs"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>getNumBitsAbs ()](#apidoc.element.mongoskin.Timestamp.prototype.getNumBitsAbs)
- description and source-code
```javascript
getNumBitsAbs = function () {
  if (this.isNegative()) {
    if (this.equals(Timestamp.MIN_VALUE)) {
      return 64;
    } else {
      return this.negate().getNumBitsAbs();
    }
  } else {
    var val = this.high_ != 0 ? this.high_ : this.low_;
    for (var bit = 31; bit > 0; bit--) {
      if ((val & (1 << bit)) != 0) {
        break;
      }
    }
    return this.high_ != 0 ? bit + 33 : bit + 1;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.greaterThan"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>greaterThan (other)](#apidoc.element.mongoskin.Timestamp.prototype.greaterThan)
- description and source-code
```javascript
greaterThan = function (other) {
  return this.compare(other) > 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.greaterThanOrEqual"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>greaterThanOrEqual (other)](#apidoc.element.mongoskin.Timestamp.prototype.greaterThanOrEqual)
- description and source-code
```javascript
greaterThanOrEqual = function (other) {
  return this.compare(other) >= 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.isNegative"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>isNegative ()](#apidoc.element.mongoskin.Timestamp.prototype.isNegative)
- description and source-code
```javascript
isNegative = function () {
  return this.high_ < 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.isOdd"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>isOdd ()](#apidoc.element.mongoskin.Timestamp.prototype.isOdd)
- description and source-code
```javascript
isOdd = function () {
  return (this.low_ & 1) == 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.isZero"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>isZero ()](#apidoc.element.mongoskin.Timestamp.prototype.isZero)
- description and source-code
```javascript
isZero = function () {
  return this.high_ == 0 && this.low_ == 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.lessThan"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>lessThan (other)](#apidoc.element.mongoskin.Timestamp.prototype.lessThan)
- description and source-code
```javascript
lessThan = function (other) {
  return this.compare(other) < 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.lessThanOrEqual"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>lessThanOrEqual (other)](#apidoc.element.mongoskin.Timestamp.prototype.lessThanOrEqual)
- description and source-code
```javascript
lessThanOrEqual = function (other) {
  return this.compare(other) <= 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.modulo"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>modulo (other)](#apidoc.element.mongoskin.Timestamp.prototype.modulo)
- description and source-code
```javascript
modulo = function (other) {
  return this.subtract(this.div(other).multiply(other));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.multiply"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>multiply (other)](#apidoc.element.mongoskin.Timestamp.prototype.multiply)
- description and source-code
```javascript
multiply = function (other) {
  if (this.isZero()) {
    return Timestamp.ZERO;
  } else if (other.isZero()) {
    return Timestamp.ZERO;
  }

  if (this.equals(Timestamp.MIN_VALUE)) {
    return other.isOdd() ? Timestamp.MIN_VALUE : Timestamp.ZERO;
  } else if (other.equals(Timestamp.MIN_VALUE)) {
    return this.isOdd() ? Timestamp.MIN_VALUE : Timestamp.ZERO;
  }

  if (this.isNegative()) {
    if (other.isNegative()) {
      return this.negate().multiply(other.negate());
    } else {
      return this.negate().multiply(other).negate();
    }
  } else if (other.isNegative()) {
    return this.multiply(other.negate()).negate();
  }

  // If both Timestamps are small, use float multiplication
  if (this.lessThan(Timestamp.TWO_PWR_24_) &&
      other.lessThan(Timestamp.TWO_PWR_24_)) {
    return Timestamp.fromNumber(this.toNumber() * other.toNumber());
  }

  // Divide each Timestamp into 4 chunks of 16 bits, and then add up 4x4 products.
  // We can skip products that would overflow.

  var a48 = this.high_ >>> 16;
  var a32 = this.high_ & 0xFFFF;
  var a16 = this.low_ >>> 16;
  var a00 = this.low_ & 0xFFFF;

  var b48 = other.high_ >>> 16;
  var b32 = other.high_ & 0xFFFF;
  var b16 = other.low_ >>> 16;
  var b00 = other.low_ & 0xFFFF;

  var c48 = 0, c32 = 0, c16 = 0, c00 = 0;
  c00 += a00 * b00;
  c16 += c00 >>> 16;
  c00 &= 0xFFFF;
  c16 += a16 * b00;
  c32 += c16 >>> 16;
  c16 &= 0xFFFF;
  c16 += a00 * b16;
  c32 += c16 >>> 16;
  c16 &= 0xFFFF;
  c32 += a32 * b00;
  c48 += c32 >>> 16;
  c32 &= 0xFFFF;
  c32 += a16 * b16;
  c48 += c32 >>> 16;
  c32 &= 0xFFFF;
  c32 += a00 * b32;
  c48 += c32 >>> 16;
  c32 &= 0xFFFF;
  c48 += a48 * b00 + a32 * b16 + a16 * b32 + a00 * b48;
  c48 &= 0xFFFF;
  return Timestamp.fromBits((c16 << 16) | c00, (c48 << 16) | c32);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.negate"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>negate ()](#apidoc.element.mongoskin.Timestamp.prototype.negate)
- description and source-code
```javascript
negate = function () {
  if (this.equals(Timestamp.MIN_VALUE)) {
    return Timestamp.MIN_VALUE;
  } else {
    return this.not().add(Timestamp.ONE);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.not"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>not ()](#apidoc.element.mongoskin.Timestamp.prototype.not)
- description and source-code
```javascript
not = function () {
  return Timestamp.fromBits(~this.low_, ~this.high_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.notEquals"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>notEquals (other)](#apidoc.element.mongoskin.Timestamp.prototype.notEquals)
- description and source-code
```javascript
notEquals = function (other) {
  return (this.high_ != other.high_) || (this.low_ != other.low_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.or"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>or (other)](#apidoc.element.mongoskin.Timestamp.prototype.or)
- description and source-code
```javascript
or = function (other) {
  return Timestamp.fromBits(this.low_ | other.low_, this.high_ | other.high_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.shiftLeft"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>shiftLeft (numBits)](#apidoc.element.mongoskin.Timestamp.prototype.shiftLeft)
- description and source-code
```javascript
shiftLeft = function (numBits) {
  numBits &= 63;
  if (numBits == 0) {
    return this;
  } else {
    var low = this.low_;
    if (numBits < 32) {
      var high = this.high_;
      return Timestamp.fromBits(
                 low << numBits,
                 (high << numBits) | (low >>> (32 - numBits)));
    } else {
      return Timestamp.fromBits(0, low << (numBits - 32));
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.shiftRight"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>shiftRight (numBits)](#apidoc.element.mongoskin.Timestamp.prototype.shiftRight)
- description and source-code
```javascript
shiftRight = function (numBits) {
  numBits &= 63;
  if (numBits == 0) {
    return this;
  } else {
    var high = this.high_;
    if (numBits < 32) {
      var low = this.low_;
      return Timestamp.fromBits(
                 (low >>> numBits) | (high << (32 - numBits)),
                 high >> numBits);
    } else {
      return Timestamp.fromBits(
                 high >> (numBits - 32),
                 high >= 0 ? 0 : -1);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.shiftRightUnsigned"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>shiftRightUnsigned (numBits)](#apidoc.element.mongoskin.Timestamp.prototype.shiftRightUnsigned)
- description and source-code
```javascript
shiftRightUnsigned = function (numBits) {
  numBits &= 63;
  if (numBits == 0) {
    return this;
  } else {
    var high = this.high_;
    if (numBits < 32) {
      var low = this.low_;
      return Timestamp.fromBits(
                 (low >>> numBits) | (high << (32 - numBits)),
                 high >>> numBits);
    } else if (numBits == 32) {
      return Timestamp.fromBits(high, 0);
    } else {
      return Timestamp.fromBits(high >>> (numBits - 32), 0);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.subtract"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>subtract (other)](#apidoc.element.mongoskin.Timestamp.prototype.subtract)
- description and source-code
```javascript
subtract = function (other) {
  return this.add(other.negate());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.toInt"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>toInt ()](#apidoc.element.mongoskin.Timestamp.prototype.toInt)
- description and source-code
```javascript
toInt = function () {
  return this.low_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>toJSON ()](#apidoc.element.mongoskin.Timestamp.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.toString();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.toNumber"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>toNumber ()](#apidoc.element.mongoskin.Timestamp.prototype.toNumber)
- description and source-code
```javascript
toNumber = function () {
  return this.high_ * Timestamp.TWO_PWR_32_DBL_ +
         this.getLowBitsUnsigned();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.toString"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>toString (opt_radix)](#apidoc.element.mongoskin.Timestamp.prototype.toString)
- description and source-code
```javascript
toString = function (opt_radix) {
  var radix = opt_radix || 10;
  if (radix < 2 || 36 < radix) {
    throw Error('radix out of range: ' + radix);
  }

  if (this.isZero()) {
    return '0';
  }

  if (this.isNegative()) {
    if (this.equals(Timestamp.MIN_VALUE)) {
      // We need to change the Timestamp value before it can be negated, so we remove
      // the bottom-most digit in this base and then recurse to do the rest.
      var radixTimestamp = Timestamp.fromNumber(radix);
      var div = this.div(radixTimestamp);
      var rem = div.multiply(radixTimestamp).subtract(this);
      return div.toString(radix) + rem.toInt().toString(radix);
    } else {
      return '-' + this.negate().toString(radix);
    }
  }

  // Do several (6) digits each time through the loop, so as to
  // minimize the calls to the very expensive emulated div.
  var radixToPower = Timestamp.fromNumber(Math.pow(radix, 6));

  var rem = this;
  var result = '';
  while (true) {
    var remDiv = rem.div(radixToPower);
    var intval = rem.subtract(remDiv.multiply(radixToPower)).toInt();
    var digits = intval.toString(radix);

    rem = remDiv;
    if (rem.isZero()) {
      return digits + result;
    } else {
      while (digits.length < 6) {
        digits = '0' + digits;
      }
      result = '' + digits + result;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.Timestamp.prototype.xor"></a>[function <span class="apidocSignatureSpan">mongoskin.Timestamp.prototype.</span>xor (other)](#apidoc.element.mongoskin.Timestamp.prototype.xor)
- description and source-code
```javascript
xor = function (other) {
  return Timestamp.fromBits(this.low_ ^ other.low_, this.high_ ^ other.high_);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.admin"></a>[module mongoskin.admin](#apidoc.module.mongoskin.admin)

#### <a name="apidoc.element.mongoskin.admin.SkinAdmin"></a>[function <span class="apidocSignatureSpan">mongoskin.admin.</span>SkinAdmin ()](#apidoc.element.mongoskin.admin.SkinAdmin)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.collection"></a>[module mongoskin.collection](#apidoc.module.mongoskin.collection)

#### <a name="apidoc.element.mongoskin.collection.SkinCollection"></a>[function <span class="apidocSignatureSpan">mongoskin.collection.</span>SkinCollection ()](#apidoc.element.mongoskin.collection.SkinCollection)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.connect"></a>[module mongoskin.connect](#apidoc.module.mongoskin.connect)

#### <a name="apidoc.element.mongoskin.connect.connect"></a>[function <span class="apidocSignatureSpan">mongoskin.</span>connect (url, options, callback)](#apidoc.element.mongoskin.connect.connect)
- description and source-code
```javascript
connect = function (url, options, callback) {
  var args = Array.prototype.slice.call(arguments, 1);
  callback = typeof args[args.length - 1] == 'function' ? args.pop() : null;
  options = args.length ? args.shift() : null;
  options = options || {};

  // Validate options object
  var err = validOptions(options);

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Return a promise
  if(typeof callback != 'function') {
    return new promiseLibrary(function(resolve, reject) {
      // Did we have a validation error
      if(err) return reject(err);
      // Attempt to connect
      connect(url, options, function(err, db) {
        if(err) return reject(err);
        resolve(db);
      });
    });
  }

  // Did we have a validation error
  if(err) return callback(err);
  // Fallback to callback based connect
  connect(url, options, callback);
}
```
- example usage
```shell
...
var Db = mongo.Db;
var Server = mongo.Server;
var MongoClient = mongo.MongoClient;
var ReplSetServers = mongo.ReplSetServers;
...
'''

### MongoClient.connect(...)

returns a 'Db' instance

alias origin 'MongoClient.connect(..., function(err, db) { .... })'

origin:
...
```

#### <a name="apidoc.element.mongoskin.connect.Admin"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Admin (db, topology, promiseLibrary)](#apidoc.element.mongoskin.connect.Admin)
- description and source-code
```javascript
Admin = function (db, topology, promiseLibrary) {
  if(!(this instanceof Admin)) return new Admin(db, topology);

  // Internal state
  this.s = {
      db: db
    , topology: topology
    , promiseLibrary: promiseLibrary
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.BSONRegExp"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>BSONRegExp (pattern, options)](#apidoc.element.mongoskin.connect.BSONRegExp)
- description and source-code
```javascript
function BSONRegExp(pattern, options) {
  if(!(this instanceof BSONRegExp)) return new BSONRegExp();

  // Execute
  this._bsontype = 'BSONRegExp';
  this.pattern = pattern || '';
  this.options = options || '';

  // Validate options
  for(var i = 0; i < this.options.length; i++) {
    if(!(this.options[i] == 'i'
      || this.options[i] == 'm'
      || this.options[i] == 'x'
      || this.options[i] == 'l'
      || this.options[i] == 's'
      || this.options[i] == 'u'
    )) {
      throw new Error('the regular expression options [' + this.options[i] + "] is not supported");
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Binary"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Binary (buffer, subType)](#apidoc.element.mongoskin.connect.Binary)
- description and source-code
```javascript
function Binary(buffer, subType) {
  if(!(this instanceof Binary)) return new Binary(buffer, subType);

  this._bsontype = 'Binary';

  if(buffer instanceof Number) {
    this.sub_type = buffer;
    this.position = 0;
  } else {
    this.sub_type = subType == null ? BSON_BINARY_SUBTYPE_DEFAULT : subType;
    this.position = 0;
  }

  if(buffer != null && !(buffer instanceof Number)) {
    // Only accept Buffer, Uint8Array or Arrays
    if(typeof buffer == 'string') {
      // Different ways of writing the length of the string for the different types
      if(typeof Buffer != 'undefined') {
        this.buffer = new Buffer(buffer);
      } else if(typeof Uint8Array != 'undefined' || (Object.prototype.toString.call(buffer) == '[object Array]')) {
        this.buffer = writeStringToArray(buffer);
      } else {
        throw new Error("only String, Buffer, Uint8Array or Array accepted");
      }
    } else {
      this.buffer = buffer;
    }
    this.position = buffer.length;
  } else {
    if(typeof Buffer != 'undefined') {
      this.buffer =  new Buffer(Binary.BUFFER_SIZE);
    } else if(typeof Uint8Array != 'undefined'){
      this.buffer = new Uint8Array(new ArrayBuffer(Binary.BUFFER_SIZE));
    } else {
      this.buffer = new Array(Binary.BUFFER_SIZE);
    }
    // Set position to start of buffer
    this.position = 0;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Chunk"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Chunk (file, mongoObject, writeConcern)](#apidoc.element.mongoskin.connect.Chunk)
- description and source-code
```javascript
Chunk = function (file, mongoObject, writeConcern) {
  if(!(this instanceof Chunk)) return new Chunk(file, mongoObject);

  this.file = file;
  var mongoObjectFinal = mongoObject == null ? {} : mongoObject;
  this.writeConcern = writeConcern || {w:1};
  this.objectId = mongoObjectFinal._id == null ? new ObjectID() : mongoObjectFinal._id;
  this.chunkNumber = mongoObjectFinal.n == null ? 0 : mongoObjectFinal.n;
  this.data = new Binary();

  if(typeof mongoObjectFinal.data == "string") {
    var buffer = new Buffer(mongoObjectFinal.data.length);
    buffer.write(mongoObjectFinal.data, 0, mongoObjectFinal.data.length, 'binary');
    this.data = new Binary(buffer);
  } else if(Array.isArray(mongoObjectFinal.data)) {
    buffer = new Buffer(mongoObjectFinal.data.length);
    var data = mongoObjectFinal.data.join('');
    buffer.write(data, 0, data.length, 'binary');
    this.data = new Binary(buffer);
  } else if(mongoObjectFinal.data && mongoObjectFinal.data._bsontype === 'Binary') {
    this.data = mongoObjectFinal.data;
  } else if(!Buffer.isBuffer(mongoObjectFinal.data) && !(mongoObjectFinal.data == null)){
    throw Error("Illegal chunk format");
  }

  // Update position
  this.internalPosition = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Code"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Code (code, scope)](#apidoc.element.mongoskin.connect.Code)
- description and source-code
```javascript
function Code(code, scope) {
  if(!(this instanceof Code)) return new Code(code, scope);
  this._bsontype = 'Code';
  this.code = code;
  this.scope = scope;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Collection (db, topology, dbName, name, pkFactory, options)](#apidoc.element.mongoskin.connect.Collection)
- description and source-code
```javascript
Collection = function (db, topology, dbName, name, pkFactory, options) {
  checkCollectionName(name);

  // Unpack variables
  var internalHint = null;
  var slaveOk = options == null || options.slaveOk == null ? db.slaveOk : options.slaveOk;
  var serializeFunctions = options == null || options.serializeFunctions == null ? db.s.options.serializeFunctions : options.serializeFunctions
;
  var raw = options == null || options.raw == null ? db.s.options.raw : options.raw;
  var promoteLongs = options == null || options.promoteLongs == null ? db.s.options.promoteLongs : options.promoteLongs;
  var promoteValues = options == null || options.promoteValues == null ? db.s.options.promoteValues : options.promoteValues;
  var promoteBuffers = options == null || options.promoteBuffers == null ? db.s.options.promoteBuffers : options.promoteBuffers;
  var readPreference = null;
  var collectionHint = null;
  var namespace = f("%s.%s", dbName, name);

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Assign the right collection level readPreference
  if(options && options.readPreference) {
    readPreference = options.readPreference;
  } else if(db.options.readPreference) {
    readPreference = db.options.readPreference;
  }

  // Set custom primary key factory if provided
  pkFactory = pkFactory == null
    ? ObjectID
    : pkFactory;

  // Internal state
  this.s = {
    // Set custom primary key factory if provided
      pkFactory: pkFactory
    // Db
    , db: db
    // Topology
    , topology: topology
    // dbName
    , dbName: dbName
    // Options
    , options: options
    // Namespace
    , namespace: namespace
    // Read preference
    , readPreference: readPreference
    // SlaveOK
    , slaveOk: slaveOk
    // Serialize functions
    , serializeFunctions: serializeFunctions
    // Raw
    , raw: raw
    // promoteLongs
    , promoteLongs: promoteLongs
    // promoteValues
    , promoteValues: promoteValues
    // promoteBuffers
    , promoteBuffers: promoteBuffers
    // internalHint
    , internalHint: internalHint
    // collectionHint
    , collectionHint: collectionHint
    // Name
    , name: name
    // Promise library
    , promiseLibrary: promiseLibrary
    // Read Concern
    , readConcern: options.readConcern
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.CoreConnection"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>CoreConnection (messageHandler, options)](#apidoc.element.mongoskin.connect.CoreConnection)
- description and source-code
```javascript
CoreConnection = function (messageHandler, options) {
  // Add event listener
  EventEmitter.call(this);
  // Set empty if no options passed
  this.options = options || {};
  // Identification information
  this.id = _id++;
  // Logger instance
  this.logger = Logger('Connection', options);
  // No bson parser passed in
  if(!options.bson) throw new Error("must pass in valid bson parser");
  // Get bson parser
  this.bson = options.bson;
  // Grouping tag used for debugging purposes
  this.tag = options.tag;
  // Message handler
  this.messageHandler = messageHandler;

  // Max BSON message size
  this.maxBsonMessageSize = options.maxBsonMessageSize || (1024 * 1024 * 16 * 4);
  // Debug information
  if(this.logger.isDebug()) this.logger.debug(f('creating connection %s with options [%s]', this.id, JSON.stringify(debugOptions
(debugFields, options))));

  // Default options
  this.port = options.port || 27017;
  this.host = options.host || 'localhost';
  this.keepAlive = typeof options.keepAlive == 'boolean' ? options.keepAlive : true;
  this.keepAliveInitialDelay = options.keepAliveInitialDelay || 0;
  this.noDelay = typeof options.noDelay == 'boolean' ? options.noDelay : true;
  this.connectionTimeout = options.connectionTimeout || 0;
  this.socketTimeout = options.socketTimeout || 0;

  // If connection was destroyed
  this.destroyed = false;

  // Check if we have a domain socket
  this.domainSocket = this.host.indexOf('\/') != -1;

  // Serialize commands using function
  this.singleBufferSerializtion = typeof options.singleBufferSerializtion == 'boolean' ? options.singleBufferSerializtion : true
;
  this.serializationFunction = this.singleBufferSerializtion ? 'toBinUnified' : 'toBin';

  // SSL options
  this.ca = options.ca || null;
  this.crl = options.crl || null;
  this.cert = options.cert || null;
  this.key = options.key || null;
  this.passphrase = options.passphrase || null;
  this.ssl = typeof options.ssl == 'boolean' ? options.ssl : false;
  this.rejectUnauthorized = typeof options.rejectUnauthorized == 'boolean' ? options.rejectUnauthorized : true;
  this.checkServerIdentity = typeof options.checkServerIdentity == 'boolean'
    || typeof options.checkServerIdentity == 'function' ? options.checkServerIdentity : true;

  // If ssl not enabled
  if(!this.ssl) this.rejectUnauthorized = false;

  // Response options
  this.responseOptions = {
    promoteLongs: typeof options.promoteLongs == 'boolean' ?  options.promoteLongs : true,
    promoteValues: typeof options.promoteValues == 'boolean' ? options.promoteValues : true,
    promoteBuffers: typeof options.promoteBuffers == 'boolean' ? options.promoteBuffers: false
  }

  // Flushing
  this.flushing = false;
  this.queue = [];

  // Internal state
  this.connection = null;
  this.writeStream = null;

  // Create hash method
  var hash = crypto.createHash('sha1');
  hash.update(f('%s:%s', this.host, this.port));

  // Create a hash name
  this.hashedName = hash.digest('hex');

  // All operations in flight on the connection
  this.workItems = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.CoreServer"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>CoreServer (options)](#apidoc.element.mongoskin.connect.CoreServer)
- description and source-code
```javascript
CoreServer = function (options) {
  options = options || {};

  // Add event listener
  EventEmitter.call(this);

  // Server instance id
  this.id = id++;

  // Internal state
  this.s = {
    // Options
    options: options,
    // Logger
    logger: Logger('Server', options),
    // Factory overrides
    Cursor: options.cursorFactory || BasicCursor,
    // BSON instance
    bson: options.bson || new BSON([BSON.Binary, BSON.Code, BSON.DBRef, BSON.Decimal128,
      BSON.Double, BSON.Int32, BSON.Long, BSON.Map, BSON.MaxKey, BSON.MinKey,
      BSON.ObjectId, BSON.BSONRegExp, BSON.Symbol, BSON.Timestamp]),
    // Pool
    pool: null,
    // Disconnect handler
    disconnectHandler: options.disconnectHandler,
    // Monitor thread (keeps the connection alive)
    monitoring: typeof options.monitoring == 'boolean' ? options.monitoring : true,
    // Is the server in a topology
    inTopology: typeof options.inTopology == 'boolean' ? options.inTopology : false,
    // Monitoring timeout
    monitoringInterval: typeof options.monitoringInterval == 'number'
      ? options.monitoringInterval
      : 5000,
    // Topology id
    topologyId: -1
  }

  // Curent ismaster
  this.ismaster = null;
  // Current ping time
  this.lastIsMasterMS = -1;
  // The monitoringProcessId
  this.monitoringProcessId = null;
  // Initial connection
  this.initalConnect = true;
  // Wire protocol handler, default to oldest known protocol handler
  // this gets changed when the first ismaster is called.
  this.wireProtocolHandler = new PreTwoSixWireProtocolSupport();
  // Default type
  this._type = 'server';
  // Set the client info
  this.clientInfo = createClientInfo(options);

  // Max Stalleness values
  // last time we updated the ismaster state
  this.lastUpdateTime = 0;
  // Last write time
  this.lastWriteDate = 0;
  // Stalleness
  this.staleness = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Cursor (bson, ns, cmd, options, topology, topologyOptions)](#apidoc.element.mongoskin.connect.Cursor)
- description and source-code
```javascript
Cursor = function (bson, ns, cmd, options, topology, topologyOptions) {
  CoreCursor.apply(this, Array.prototype.slice.call(arguments, 0));
  var self = this;
  var state = Cursor.INIT;
  var streamOptions = {};

  // Tailable cursor options
  var numberOfRetries = options.numberOfRetries || 5;
  var tailableRetryInterval = options.tailableRetryInterval || 500;
  var currentNumberOfRetries = numberOfRetries;

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Set up
  Readable.call(this, {objectMode: true});

  // Internal cursor state
  this.s = {
    // Tailable cursor options
      numberOfRetries: numberOfRetries
    , tailableRetryInterval: tailableRetryInterval
    , currentNumberOfRetries: currentNumberOfRetries
    // State
    , state: state
    // Stream options
    , streamOptions: streamOptions
    // BSON
    , bson: bson
    // Namespace
    , ns: ns
    // Command
    , cmd: cmd
    // Options
    , options: options
    // Topology
    , topology: topology
    // Topology options
    , topologyOptions: topologyOptions
    // Promise library
    , promiseLibrary: promiseLibrary
    // Current doc
    , currentDoc: null
  }

  // Translate correctly
  if(self.s.options.noCursorTimeout == true) {
    self.addCursorFlag('noCursorTimeout', true);
  }

  // Set the sort value
  this.sortValue = self.s.cmd.sort;

  // Get the batchSize
  var batchSize = cmd.cursor && cmd.cursor.batchSize
    ? cmd.cursor && cmd.cursor.batchSize
    : (options.cursor && options.cursor.batchSize ? options.cursor.batchSize : 1000);

  // Set the batchSize
  this.setCursorBatchSize(batchSize);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.DBRef"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>DBRef (namespace, oid, db)](#apidoc.element.mongoskin.connect.DBRef)
- description and source-code
```javascript
function DBRef(namespace, oid, db) {
  if(!(this instanceof DBRef)) return new DBRef(namespace, oid, db);

  this._bsontype = 'DBRef';
  this.namespace = namespace;
  this.oid = oid;
  this.db = db;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Db (databaseName, topology, options)](#apidoc.element.mongoskin.connect.Db)
- description and source-code
```javascript
Db = function (databaseName, topology, options) {
  options = options || {};
  if(!(this instanceof Db)) return new Db(databaseName, topology, options);
  EventEmitter.call(this);
  var self = this;

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Ensure we put the promiseLib in the options
  options.promiseLibrary = promiseLibrary;

  // var self = this;  // Internal state of the db object
  this.s = {
    // Database name
      databaseName: databaseName
    // DbCache
    , dbCache: {}
    // Children db's
    , children: []
    // Topology
    , topology: topology
    // Options
    , options: options
    // Logger instance
    , logger: Logger('Db', options)
    // Get the bson parser
    , bson: topology ? topology.bson : null
    // Authsource if any
    , authSource: options.authSource
    // Unpack read preference
    , readPreference: options.readPreference
    // Set buffermaxEntries
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : -1
    // Parent db (if chained)
    , parentDb: options.parentDb || null
    // Set up the primary key factory or fallback to ObjectID
    , pkFactory: options.pkFactory || ObjectID
    // Get native parser
    , nativeParser: options.nativeParser || options.native_parser
    // Promise library
    , promiseLibrary: promiseLibrary
    // No listener
    , noListener: typeof options.noListener == 'boolean' ? options.noListener : false
    // ReadConcern
    , readConcern: options.readConcern
  }

  // Ensure we have a valid db name
  validateDatabaseName(self.s.databaseName);

  // Add a read Only property
  getSingleProperty(this, 'serverConfig', self.s.topology);
  getSingleProperty(this, 'bufferMaxEntries', self.s.bufferMaxEntries);
  getSingleProperty(this, 'databaseName', self.s.databaseName);

  // This is a child db, do not register any listeners
  if(options.parentDb) return;
  if(this.s.noListener) return;

  // Add listeners
  topology.on('error', createListener(self, 'error', self));
  topology.on('timeout', createListener(self, 'timeout', self));
  topology.on('close', createListener(self, 'close', self));
  topology.on('parseError', createListener(self, 'parseError', self));
  topology.once('open', createListener(self, 'open', self));
  topology.once('fullsetup', createListener(self, 'fullsetup', self));
  topology.once('all', createListener(self, 'all', self));
  topology.on('reconnect', createListener(self, 'reconnect', self));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Decimal128"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Decimal128 (bytes)](#apidoc.element.mongoskin.connect.Decimal128)
- description and source-code
```javascript
Decimal128 = function (bytes) {
  this._bsontype = 'Decimal128';
  this.bytes = bytes;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Double"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Double (value)](#apidoc.element.mongoskin.connect.Double)
- description and source-code
```javascript
function Double(value) {
  if(!(this instanceof Double)) return new Double(value);

  this._bsontype = 'Double';
  this.value = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridFSBucket"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>GridFSBucket (db, options)](#apidoc.element.mongoskin.connect.GridFSBucket)
- description and source-code
```javascript
function GridFSBucket(db, options) {
  Emitter.apply(this);
  this.setMaxListeners(0);

  if (options && typeof options === 'object') {
    options = shallowClone(options);
    var keys = Object.keys(DEFAULT_GRIDFS_BUCKET_OPTIONS);
    for (var i = 0; i < keys.length; ++i) {
      if (!options[keys[i]]) {
        options[keys[i]] = DEFAULT_GRIDFS_BUCKET_OPTIONS[keys[i]];
      }
    }
  } else {
    options = DEFAULT_GRIDFS_BUCKET_OPTIONS;
  }

  this.s = {
    db: db,
    options: options,
    _chunksCollection: db.collection(options.bucketName + '.chunks'),
    _filesCollection: db.collection(options.bucketName + '.files'),
    checkedIndexes: false,
    calledOpenUploadStream: false,
    promiseLibrary: db.s.promiseLibrary ||
      (typeof global.Promise == 'function' ? global.Promise : require('es6-promise').Promise)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>GridStore (db, id, filename, mode, options)](#apidoc.element.mongoskin.connect.GridStore)
- description and source-code
```javascript
function GridStore(db, id, filename, mode, options) {
  if(!(this instanceof GridStore)) return new GridStore(db, id, filename, mode, options);
  this.db = db;

  // Handle options
  if(typeof options === 'undefined') options = {};
  // Handle mode
  if(typeof mode === 'undefined') {
    mode = filename;
    filename = undefined;
  } else if(typeof mode == 'object') {
    options = mode;
    mode = filename;
    filename = undefined;
  }

  if(id && id._bsontype == 'ObjectID') {
    this.referenceBy = REFERENCE_BY_ID;
    this.fileId = id;
    this.filename = filename;
  } else if(typeof filename == 'undefined') {
    this.referenceBy = REFERENCE_BY_FILENAME;
    this.filename = id;
    if (mode.indexOf('w') != null) {
      this.fileId = new ObjectID();
    }
  } else {
    this.referenceBy = REFERENCE_BY_ID;
    this.fileId = id;
    this.filename = filename;
  }

  // Set up the rest
  this.mode = mode == null ? "r" : mode;
  this.options = options || {};

  // Opened
  this.isOpen = false;

  // Set the root if overridden
  this.root = this.options['root'] == null ? GridStore.DEFAULT_ROOT_COLLECTION : this.options['root'];
  this.position = 0;
  this.readPreference = this.options.readPreference || db.options.readPreference || ReadPreference.PRIMARY;
  this.writeConcern = _getWriteConcern(db, this.options);
  // Set default chunk size
  this.internalChunkSize = this.options['chunkSize'] == null ? Chunk.DEFAULT_CHUNK_SIZE : this.options['chunkSize'];

  // Get the promiseLibrary
  var promiseLibrary = this.options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Set the promiseLibrary
  this.promiseLibrary = promiseLibrary;

  Object.defineProperty(this, "chunkSize", { enumerable: true
   , get: function () {
       return this.internalChunkSize;
     }
   , set: function(value) {
       if(!(this.mode[0] == "w" && this.position == 0 && this.uploadDate == null)) {
         this.internalChunkSize = this.internalChunkSize;
       } else {
         this.internalChunkSize = value;
       }
     }
  });

  Object.defineProperty(this, "md5", { enumerable: true
   , get: function () {
       return this.internalMd5;
     }
  });

  Object.defineProperty(this, "chunkNumber", { enumerable: true
   , get: function () {
       return this.currentChunk && this.currentChunk.chunkNumber ? this.currentChunk.chunkNumber : null;
     }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Int32"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Int32 (value)](#apidoc.element.mongoskin.connect.Int32)
- description and source-code
```javascript
Int32 = function (value) {
  if(!(this instanceof Int32)) return new Int32(value);

  this._bsontype = 'Int32';
  this.value = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Logger"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Logger (className, options)](#apidoc.element.mongoskin.connect.Logger)
- description and source-code
```javascript
Logger = function (className, options) {
  if(!(this instanceof Logger)) return new Logger(className, options);
  options = options || {};

  // Current reference
  this.className = className;

  // Current logger
  if(options.logger) {
    currentLogger = options.logger;
  } else if(currentLogger == null) {
    currentLogger = console.log;
  }

  // Set level of logging, default is error
  if(options.loggerLevel) {
    level = options.loggerLevel || 'error';
  }

  // Add all class names
  if(filteredClasses[this.className] == null) classFilters[this.className] =  true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Long"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Long (low, high)](#apidoc.element.mongoskin.connect.Long)
- description and source-code
```javascript
function Long(low, high) {
  if(!(this instanceof Long)) return new Long(low, high);

  this._bsontype = 'Long';
<span class="apidocCodeCommentSpan">  /**
   * @type {number}
   * @ignore
   */
</span>  this.low_ = low | 0;  // force into 32 signed bits.

  /**
   * @type {number}
   * @ignore
   */
  this.high_ = high | 0;  // force into 32 signed bits.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Map"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Map ()](#apidoc.element.mongoskin.connect.Map)
- description and source-code
```javascript
function Map() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.MaxKey"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>MaxKey ()](#apidoc.element.mongoskin.connect.MaxKey)
- description and source-code
```javascript
function MaxKey() {
  if(!(this instanceof MaxKey)) return new MaxKey();

  this._bsontype = 'MaxKey';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.MinKey"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>MinKey ()](#apidoc.element.mongoskin.connect.MinKey)
- description and source-code
```javascript
function MinKey() {
  if(!(this instanceof MinKey)) return new MinKey();

  this._bsontype = 'MinKey';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.MongoClient"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>MongoClient ()](#apidoc.element.mongoskin.connect.MongoClient)
- description and source-code
```javascript
function MongoClient() {
<span class="apidocCodeCommentSpan">  /**
   * The callback format for results
   * @callback MongoClient~connectCallback
   * @param {MongoError} error An error instance representing the error during the execution.
   * @param {Db} db The connected database.
   */
</span>
  /**
   * Connect to MongoDB using a url as documented at
   *
   *  docs.mongodb.org/manual/reference/connection-string/
   *
   * Note that for replicasets the replicaSet query parameter is required in the 2.0 driver
   *
   * @method
   * @param {string} url The connection URI string
   * @param {object} [options] Optional settings.
   * @param {number} [options.poolSize=5] poolSize The maximum size of the individual server pool.
   * @param {boolean} [options.ssl=false] Enable SSL connection.
   * @param {Buffer} [options.sslCA=undefined] SSL Certificate store binary buffer
   * @param {Buffer} [options.sslCRL=undefined] SSL Certificate revocation list binary buffer
   * @param {Buffer} [options.sslCert=undefined] SSL Certificate binary buffer
   * @param {Buffer} [options.sslKey=undefined] SSL Key file binary buffer
   * @param {string} [options.sslPass=undefined] SSL Certificate pass phrase
   * @param {boolean|function} [options.checkServerIdentity=true] Ensure we check server identify during SSL, set to false to disable
 checking. Only works for Node 0.12.x or higher. You can pass in a boolean or your own checkServerIdentity override function.
   * @param {boolean} [options.autoReconnect=true] Enable autoReconnect for single server instances
   * @param {boolean} [options.noDelay=true] TCP Connection no delay
   * @param {boolean} [options.keepAlive=0] The number of milliseconds to wait before initiating keepAlive on the TCP socket.
   * @param {number} [options.connectTimeoutMS=30000] TCP Connection timeout setting
   * @param {number} [options.socketTimeoutMS=30000] TCP Socket timeout setting
   * @param {number} [options.reconnectTries=30] Server attempt to reconnect #times
   * @param {number} [options.reconnectInterval=1000] Server will wait # milliseconds between retries
   * @param {boolean} [options.ha=true] Control if high availability monitoring runs for Replicaset or Mongos proxies.
   * @param {number} [options.haInterval=10000] The High availability period for replicaset inquiry
   * @param {string} [options.replicaSet=undefined] The Replicaset set name
   * @param {number} [options.secondaryAcceptableLatencyMS=15] Cutoff latency point in MS for Replicaset member selection
   * @param {number} [options.acceptableLatencyMS=15] Cutoff latency point in MS for Mongos proxies selection.
   * @param {boolean} [options.connectWithNoPrimary=false] Sets if the driver should connect even if no primary is available
   * @param {string} [options.authSource=undefined] Define the database to authenticate against
   * @param {(number|string)} [options.w=null] The write concern.
   * @param {number} [options.wtimeout=null] The write concern timeout.
   * @param {boolean} [options.j=false] Specify a journal write concern.
   * @param {boolean} [options.forceServerObjectId=false] Force server to assign _id values instead of driver.
   * @param {boolean} [options.serializeFunctions=false] Serialize functions on any object.
   * @param {Boolean} [options.ignoreUndefined=false] Specify if the BSON serializer should ignore undefined fields.
   * @param {boolean} [options.raw=false] Return document results as raw BSON buffers.
   * @param {boolean} [options.promoteLongs=true] Promotes Long values to number if they fit inside the 53 bits resolution.
   * @param {boolean} [options.promoteBuffers=false] Promotes Binary BSON values to native Node Buffers.
   * @param {boolean} [options.promoteValues=true] Promotes BSON values to native types where possible, set to false to only receive
 wrapper types.
   * @param {number} [options.bufferMaxEntries=-1] Sets a cap on how many operations the driver will buffer up before giving up
on getting a working connection, default is -1 which is unlimited.
   * @param {(ReadPreference|string)} [options.readPreference=null] The preferred ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.MongoError"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>MongoError (message)](#apidoc.element.mongoskin.connect.MongoError)
- description and source-code
```javascript
function MongoError(message) {
  this.name = 'MongoError';
  this.message = message;
  Error.captureStackTrace(this, MongoError);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Mongos"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Mongos (servers, options)](#apidoc.element.mongoskin.connect.Mongos)
- description and source-code
```javascript
Mongos = function (servers, options) {
  if(!(this instanceof Mongos)) return new Mongos(servers, options);
  options = options || {};
  var self = this;

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Ensure all the instances are Server
  for(var i = 0; i < servers.length; i++) {
    if(!(servers[i] instanceof Server)) {
      throw MongoError.create({message: "all seed list instances must be of the Server type", driver:true});
    }
  }

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Set up event emitter
  EventEmitter.call(this);

  // Build seed list
  var seedlist = servers.map(function(x) {
    return {host: x.host, port: x.port}
  });

  // Get the reconnect option
  var reconnect = typeof options.auto_reconnect == 'boolean' ? options.auto_reconnect : true;
  reconnect = typeof options.autoReconnect == 'boolean' ? options.autoReconnect : reconnect;

  // Clone options
  var clonedOptions = mergeOptions({}, {
    disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: reconnect,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Build default client information
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create the Mongos
  var mongos = new CMongos(seedlist, clonedOptions)
  // Server capabilities
  var sCapabilities = null;

  // Internal state
  this.s = {
    // Create the Mongos
      mongos: mongos
    // Server capabilities
    , sCapabilities: sCapabilities
    // Debug turned on
    , debug: clonedOptions.debug
    // Store option defaults
    , storeOptions: storeOptions
    // Cloned options
    , clonedOptions: clonedOptions
    // Actual store of callbacks
    , store: store
    // Options
    , options: options
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.ObjectID"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>ObjectID (id)](#apidoc.element.mongoskin.connect.ObjectID)
- description and source-code
```javascript
function ObjectID(id) {
  // Duck-typing to support ObjectId from different npm packages
  if(id instanceof ObjectID) return id;
  if(!(this instanceof ObjectID)) return new ObjectID(id);

  this._bsontype = 'ObjectID';

  // The most common usecase (blank id, new objectId instance)
  if(id == null || typeof id == 'number') {
    // Generate a new id
    this.id = this.generate(id);
    // If we are caching the hex string
    if(ObjectID.cacheHexString) this.__id = this.toString('hex');
    // Return the object
    return;
  }

  // Check if the passed in id is valid
  var valid = ObjectID.isValid(id);

  // Throw an error if it's not a valid setup
  if(!valid && id != null){
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  } else if(valid && typeof id == 'string' && id.length == 24 && hasBufferType) {
    return new ObjectID(new Buffer(id, 'hex'));
  } else if(valid && typeof id == 'string' && id.length == 24) {
    return ObjectID.createFromHexString(id);
  } else if(id != null && id.length === 12) {
    // assume 12 byte string
    this.id = id;
  } else if(id != null && id.toHexString) {
    // Duck-typing to support ObjectId from different npm packages
    return id;
  } else {
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  }

  if(ObjectID.cacheHexString) this.__id = this.toString('hex');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.ObjectId"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>ObjectId (id)](#apidoc.element.mongoskin.connect.ObjectId)
- description and source-code
```javascript
function ObjectID(id) {
  // Duck-typing to support ObjectId from different npm packages
  if(id instanceof ObjectID) return id;
  if(!(this instanceof ObjectID)) return new ObjectID(id);

  this._bsontype = 'ObjectID';

  // The most common usecase (blank id, new objectId instance)
  if(id == null || typeof id == 'number') {
    // Generate a new id
    this.id = this.generate(id);
    // If we are caching the hex string
    if(ObjectID.cacheHexString) this.__id = this.toString('hex');
    // Return the object
    return;
  }

  // Check if the passed in id is valid
  var valid = ObjectID.isValid(id);

  // Throw an error if it's not a valid setup
  if(!valid && id != null){
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  } else if(valid && typeof id == 'string' && id.length == 24 && hasBufferType) {
    return new ObjectID(new Buffer(id, 'hex'));
  } else if(valid && typeof id == 'string' && id.length == 24) {
    return ObjectID.createFromHexString(id);
  } else if(id != null && id.length === 12) {
    // assume 12 byte string
    this.id = id;
  } else if(id != null && id.toHexString) {
    // Duck-typing to support ObjectId from different npm packages
    return id;
  } else {
    throw new Error("Argument passed in must be a single String of 12 bytes or a string of 24 hex characters");
  }

  if(ObjectID.cacheHexString) this.__id = this.toString('hex');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.ReadPreference"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>ReadPreference (mode, tags, options)](#apidoc.element.mongoskin.connect.ReadPreference)
- description and source-code
```javascript
ReadPreference = function (mode, tags, options) {
  if(!(this instanceof ReadPreference)) {
    return new ReadPreference(mode, tags, options);
  }

  this._type = 'ReadPreference';
  this.mode = mode;
  this.tags = tags;
  this.options =  options;

  // If no tags were passed in
  if(tags && typeof tags == 'object' && !Array.isArray(tags)) {
    if(tags.maxStalenessSeconds) {
      this.options = tags;
      this.tags = null;
    }
  }

  // Add the maxStalenessSeconds value to the read Preference
  if(this.options && this.options.maxStalenessSeconds) {
    this.maxStalenessSeconds = this.options.maxStalenessSeconds;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.ReplSet"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>ReplSet (servers, options)](#apidoc.element.mongoskin.connect.ReplSet)
- description and source-code
```javascript
ReplSet = function (servers, options) {
  if(!(this instanceof ReplSet)) return new ReplSet(servers, options);
  options = options || {};
  var self = this;
  // Set up event emitter
  EventEmitter.call(this);

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Ensure all the instances are Server
  for(var i = 0; i < servers.length; i++) {
    if(!(servers[i] instanceof Server)) {
      throw MongoError.create({message: "all seed list instances must be of the Server type", driver:true});
    }
  }

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Build seed list
  var seedlist = servers.map(function(x) {
    return {host: x.host, port: x.port}
  });

  // Clone options
  var clonedOptions = mergeOptions({}, {
    disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: false,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Client info
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create the ReplSet
  var replset = new CReplSet(seedlist, clonedOptions);

  // Listen to reconnect event
  replset.on('reconnect', function() {
    self.emit('reconnect');
    store.execute();
  });

  // Internal state
  this.s = {
    // Replicaset
    replset: replset
    // Server capabilities
    , sCapabilities: null
    // Debug tag
    , tag: options.tag
    // Store options
    , storeOptions: storeOptions
    // Cloned options
    , clonedOptions: clonedOptions
    // Store
    , store: store
    // Options
    , options: options
  }

  // Debug
  if(clonedOptions.debug) {
    // Last ismaster
    Object.defineProperty(this, 'replset', {
      enumerable:true, get: function() { return replset; }
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Server"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Server (host, port, options)](#apidoc.element.mongoskin.connect.Server)
- description and source-code
```javascript
Server = function (host, port, options) {
  options = options || {};
  if(!(this instanceof Server)) return new Server(host, port, options);
  EventEmitter.call(this);
  var self = this;

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Stored options
  var storeOptions = {
      force: false
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : MAX_JS_INT
  }

  // Shared global store
  var store = options.store || new Store(self, storeOptions);

  // Detect if we have a socket connection
  if(host.indexOf('\/') != -1) {
    if(port != null && typeof port == 'object') {
      options = port;
      port = null;
    }
  } else if(port == null) {
    throw MongoError.create({message: 'port must be specified', driver:true});
  }

  // Get the reconnect option
  var reconnect = typeof options.auto_reconnect == 'boolean' ? options.auto_reconnect : true;
  reconnect = typeof options.autoReconnect == 'boolean' ? options.autoReconnect : reconnect;

  // Clone options
  var clonedOptions = mergeOptions({}, {
    host: host, port: port, disconnectHandler: store,
    cursorFactory: Cursor,
    reconnect: reconnect,
    emitError: typeof options.emitError == 'boolean' ? options.emitError : true,
    size: typeof options.poolSize == 'number' ? options.poolSize : 5
  });

  // Translate any SSL options and other connectivity options
  clonedOptions = translateOptions(clonedOptions, options);

  // Socket options
  var socketOptions = options.socketOptions && Object.keys(options.socketOptions).length > 0
    ? options.socketOptions : options;

  // Translate all the options to the mongodb-core ones
  clonedOptions = translateOptions(clonedOptions, socketOptions);
  if(typeof clonedOptions.keepAlive == 'number') {
    clonedOptions.keepAliveInitialDelay = clonedOptions.keepAlive;
    clonedOptions.keepAlive = clonedOptions.keepAlive > 0;
  }

  // Build default client information
  this.clientInfo = {
    driver: {
      name: "nodejs",
      version: driverVersion
    },
    os: {
      type: type,
      name: name,
      architecture: architecture,
      version: release
    },
    platform: nodejsversion
  }

  // Build default client information
  clonedOptions.clientInfo = this.clientInfo;
  // Do we have an application specific string
  if(options.appname) {
    clonedOptions.clientInfo.application = { name: options.appname };
  }

  // Create an instance of a server instance from mongodb-core
  var server = new CServer(clonedOptions);

  // Define the internal properties
  this.s = {
    // Create an instance of a server instance from mongodb-core
      server: server
    // Server capabilities
    , sCapabilities: null
    // Cloned options
    , clonedOptions: clonedOptions
    // Reconnect
    , reconnect: clonedOptions.reconnect
    // Emit error
    , emitError: clonedOptions.emitError
    // Pool size
    , poolSize: clonedOptions.size
    // Store Options
    , storeOptions: storeOptions
    // Store
    , store: store
    // Host
    , host: host
    // Port
    , port: port
    // Options
    , options: options
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Symbol"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Symbol (value)](#apidoc.element.mongoskin.connect.Symbol)
- description and source-code
```javascript
function Symbol(value) {
  if(!(this instanceof Symbol)) return new Symbol(value);
  this._bsontype = 'Symbol';
  this.value = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Timestamp"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Timestamp (low, high)](#apidoc.element.mongoskin.connect.Timestamp)
- description and source-code
```javascript
function Timestamp(low, high) {
  if(!(this instanceof Timestamp)) return new Timestamp(low, high);
  this._bsontype = 'Timestamp';
<span class="apidocCodeCommentSpan">  /**
   * @type {number}
   * @ignore
   */
</span>  this.low_ = low | 0;  // force into 32 signed bits.

  /**
   * @type {number}
   * @ignore
   */
  this.high_ = high | 0;  // force into 32 signed bits.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.instrument"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>instrument (options, callback)](#apidoc.element.mongoskin.connect.instrument)
- description and source-code
```javascript
instrument = function (options, callback) {
  if(typeof options == 'function') callback = options, options = {};
  return new Instrumentation(core, options, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.connect.Admin"></a>[module mongoskin.connect.Admin](#apidoc.module.mongoskin.connect.Admin)

#### <a name="apidoc.element.mongoskin.connect.Admin.Admin"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Admin (db, topology, promiseLibrary)](#apidoc.element.mongoskin.connect.Admin.Admin)
- description and source-code
```javascript
Admin = function (db, topology, promiseLibrary) {
  if(!(this instanceof Admin)) return new Admin(db, topology);

  // Internal state
  this.s = {
      db: db
    , topology: topology
    , promiseLibrary: promiseLibrary
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.connect.Admin.prototype"></a>[module mongoskin.connect.Admin.prototype](#apidoc.module.mongoskin.connect.Admin.prototype)

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.addUser"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>addUser (username, password, options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.addUser)
- description and source-code
```javascript
addUser = function (username, password, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 2);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  options = args.length ? args.shift() : {};
  options = options || {};
  // Get the options
  options = writeConcern(options, self.s.db)
  // Set the db name to admin
  options.dbName = 'admin';

  // Execute using callback
  if(typeof callback == 'function')
    return self.s.db.addUser(username, password, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.s.db.addUser(username, password, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.authenticate"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>authenticate (username, password, options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.authenticate)
- description and source-code
```javascript
authenticate = function (username, password, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = shallowClone(options);
  options.authdb = 'admin';

  // Execute using callback
  if(typeof callback == 'function') return this.s.db.authenticate(username, password, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.s.db.authenticate(username, password, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.buildInfo"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>buildInfo (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.buildInfo)
- description and source-code
```javascript
buildInfo = function (callback) {
  var self = this;
  // Execute using callback
  if(typeof callback == 'function') return this.serverInfo(callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.serverInfo(function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.command"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>command (command, options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.command)
- description and source-code
```javascript
command = function (command, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  options = args.length ? args.shift() : {};

  // Execute using callback
  if(typeof callback == 'function') return this.s.db.executeDbAdminCommand(command, options, function(err, doc) {
    return callback != null ? callback(err, doc) : null;
  });

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.s.db.executeDbAdminCommand(command, options, function(err, doc) {
      if(err) return reject(err);
      resolve(doc);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.listDatabases"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>listDatabases (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.listDatabases)
- description and source-code
```javascript
listDatabases = function (callback) {
  var self = this;
  // Execute using callback
  if(typeof callback == 'function') return self.s.db.executeDbAdminCommand({listDatabases:1}, {}, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.s.db.executeDbAdminCommand({listDatabases:1}, {}, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.logout"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>logout (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.logout)
- description and source-code
```javascript
logout = function (callback) {
  var self = this;
  // Execute using callback
  if(typeof callback == 'function') return this.s.db.logout({dbName: 'admin'}, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.s.db.logout({dbName: 'admin'}, function(err) {
      if(err) return reject(err);
      resolve(true);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.ping"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>ping (options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.ping)
- description and source-code
```javascript
ping = function (options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 0);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);

  // Execute using callback
  if(typeof callback == 'function') return this.s.db.executeDbAdminCommand({ping: 1}, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.s.db.executeDbAdminCommand({ping: 1}, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.profilingInfo"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>profilingInfo (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.profilingInfo)
- description and source-code
```javascript
profilingInfo = function (callback) {
  var self = this;

  // Execute using callback
  if(typeof callback == 'function') return profilingInfo(self, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    profilingInfo(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.profilingLevel"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>profilingLevel (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.profilingLevel)
- description and source-code
```javascript
profilingLevel = function (callback) {
  var self = this;

  // Execute using callback
  if(typeof callback == 'function') return profilingLevel(self, callback)

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    profilingLevel(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.removeUser"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>removeUser (username, options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.removeUser)
- description and source-code
```javascript
removeUser = function (username, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  options = args.length ? args.shift() : {};
  options = options || {};
  // Get the options
  options = writeConcern(options, self.s.db)
  // Set the db name
  options.dbName = 'admin';

  // Execute using callback
  if(typeof callback == 'function')
    return self.s.db.removeUser(username, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.s.db.removeUser(username, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.replSetGetStatus"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>replSetGetStatus (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.replSetGetStatus)
- description and source-code
```javascript
replSetGetStatus = function (callback) {
  var self = this;
  // Execute using callback
  if(typeof callback == 'function') return replSetGetStatus(self, callback);
  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    replSetGetStatus(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.serverInfo"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>serverInfo (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.serverInfo)
- description and source-code
```javascript
serverInfo = function (callback) {
  var self = this;
  // Execute using callback
  if(typeof callback == 'function') return this.s.db.executeDbAdminCommand({buildinfo:1}, function(err, doc) {
    if(err != null) return callback(err, null);
    callback(null, doc);
  });

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.s.db.executeDbAdminCommand({buildinfo:1}, function(err, doc) {
      if(err) return reject(err);
      resolve(doc);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.serverStatus"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>serverStatus (callback)](#apidoc.element.mongoskin.connect.Admin.prototype.serverStatus)
- description and source-code
```javascript
serverStatus = function (callback) {
  var self = this;

  // Execute using callback
  if(typeof callback == 'function') return serverStatus(self, callback)

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    serverStatus(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.setProfilingLevel"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>setProfilingLevel (level, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.setProfilingLevel)
- description and source-code
```javascript
setProfilingLevel = function (level, callback) {
  var self = this;

  // Execute using callback
  if(typeof callback == 'function') return setProfilingLevel(self, level, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    setProfilingLevel(self, level, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Admin.prototype.validateCollection"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Admin.prototype.</span>validateCollection (collectionName, options, callback)](#apidoc.element.mongoskin.connect.Admin.prototype.validateCollection)
- description and source-code
```javascript
validateCollection = function (collectionName, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  options = args.length ? args.shift() : {};
  options = options || {};

  // Execute using callback
  if(typeof callback == 'function')
    return validateCollection(self, collectionName, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    validateCollection(self, collectionName, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.connect.Collection"></a>[module mongoskin.connect.Collection](#apidoc.module.mongoskin.connect.Collection)

#### <a name="apidoc.element.mongoskin.connect.Collection.Collection"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Collection (db, topology, dbName, name, pkFactory, options)](#apidoc.element.mongoskin.connect.Collection.Collection)
- description and source-code
```javascript
Collection = function (db, topology, dbName, name, pkFactory, options) {
  checkCollectionName(name);

  // Unpack variables
  var internalHint = null;
  var slaveOk = options == null || options.slaveOk == null ? db.slaveOk : options.slaveOk;
  var serializeFunctions = options == null || options.serializeFunctions == null ? db.s.options.serializeFunctions : options.serializeFunctions
;
  var raw = options == null || options.raw == null ? db.s.options.raw : options.raw;
  var promoteLongs = options == null || options.promoteLongs == null ? db.s.options.promoteLongs : options.promoteLongs;
  var promoteValues = options == null || options.promoteValues == null ? db.s.options.promoteValues : options.promoteValues;
  var promoteBuffers = options == null || options.promoteBuffers == null ? db.s.options.promoteBuffers : options.promoteBuffers;
  var readPreference = null;
  var collectionHint = null;
  var namespace = f("%s.%s", dbName, name);

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Assign the right collection level readPreference
  if(options && options.readPreference) {
    readPreference = options.readPreference;
  } else if(db.options.readPreference) {
    readPreference = db.options.readPreference;
  }

  // Set custom primary key factory if provided
  pkFactory = pkFactory == null
    ? ObjectID
    : pkFactory;

  // Internal state
  this.s = {
    // Set custom primary key factory if provided
      pkFactory: pkFactory
    // Db
    , db: db
    // Topology
    , topology: topology
    // dbName
    , dbName: dbName
    // Options
    , options: options
    // Namespace
    , namespace: namespace
    // Read preference
    , readPreference: readPreference
    // SlaveOK
    , slaveOk: slaveOk
    // Serialize functions
    , serializeFunctions: serializeFunctions
    // Raw
    , raw: raw
    // promoteLongs
    , promoteLongs: promoteLongs
    // promoteValues
    , promoteValues: promoteValues
    // promoteBuffers
    , promoteBuffers: promoteBuffers
    // internalHint
    , internalHint: internalHint
    // collectionHint
    , collectionHint: collectionHint
    // Name
    , name: name
    // Promise library
    , promiseLibrary: promiseLibrary
    // Read Concern
    , readConcern: options.readConcern
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.connect.Collection.prototype"></a>[module mongoskin.connect.Collection.prototype](#apidoc.module.mongoskin.connect.Collection.prototype)

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.aggregate"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>aggregate (pipeline, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.aggregate)
- description and source-code
```javascript
aggregate = function (pipeline, options, callback) {
  var self = this;

  if(Array.isArray(pipeline)) {
    // Set up callback if one is provided
    if(typeof options == 'function') {
      callback = options;
      options = {};
    }

    // If we have no options or callback we are doing
    // a cursor based aggregation
    if(options == null && callback == null) {
      options = {};
    }
  } else {
    // Aggregation pipeline passed as arguments on the method
    var args = Array.prototype.slice.call(arguments, 0);
    // Get the callback
    callback = args.pop();
    // Get the possible options object
    var opts = args[args.length - 1];
    // If it contains any of the admissible options pop it of the args
    options = opts && (opts.readPreference
      || opts.explain || opts.cursor || opts.out
      || opts.maxTimeMS || opts.allowDiskUse) ? args.pop() : {};
      // Left over arguments is the pipeline
    pipeline = args;
  }

  // Ignore readConcern option
  var ignoreReadConcern = false;

  // Build the command
  var command = { aggregate : this.s.name, pipeline : pipeline};

  // If out was specified
  if(typeof options.out == 'string') {
    pipeline.push({$out: options.out});
    // Ignore read concern
    ignoreReadConcern = true;
  } else if(pipeline.length > 0 && pipeline[pipeline.length - 1]['$out']) {
    ignoreReadConcern = true;
  }

  // Decorate command with writeConcern if out has been specified
  if(pipeline.length > 0 && pipeline[pipeline.length - 1]['$out']) {
    decorateWithWriteConcern(command, self, options);
  }

  // Have we specified collation
  decorateWithCollation(command, self, options);

  // If we have bypassDocumentValidation set
  if(typeof options.bypassDocumentValidation == 'boolean') {
    command.bypassDocumentValidation = options.bypassDocumentValidation;
  }

  // Do we have a readConcern specified
  if(!ignoreReadConcern && this.s.readConcern) {
    command.readConcern = this.s.readConcern;
  }

  // If we have allowDiskUse defined
  if(options.allowDiskUse) command.allowDiskUse = options.allowDiskUse;
  if(typeof options.maxTimeMS == 'number') command.maxTimeMS = options.maxTimeMS;

  options = shallowClone(options);
  // Ensure we have the right read preference inheritance
  options = getReadPreference(this, options, this.s.db, this);

  // If explain has been specified add it
  if(options.explain) command.explain = options.explain;

  // Validate that cursor options is valid
  if(options.cursor != null && typeof options.cursor != 'object') {
    throw toError('cursor options must be an object');
  }

  // promiseLibrary
  options.promiseLibrary = this.s.promiseLibrary;

  // Set the AggregationCursor constructor
  options.cursorFactory = AggregationCursor;
  if(typeof callback != 'function') {
    if(!this.s.topology.capabilities()) {
      throw new MongoError('cannot connect to server');
    }

    if(this.s.topology.capabilities().hasAggregationCursor) {
      options.cursor = options.cursor || { batchSize : 1000 };
      command.cursor = options.cursor;
    }

    // Allow disk usage command
    if(typeof options.allowDiskUse == 'boolean') command.allowDiskUse = options.allowDiskUse;
    if(typeof options.maxTimeMS == 'number') command.maxTimeMS = options.maxTimeMS;

    // Execute the cursor
    return this.s.topology.cursor(this.s.namespace, command, options);
  }

  // We do not allow cursor
  if(options.cursor) {
    return this.s.topology.cursor(this.s.namespace, command, options);
  }

  // Execute the command
  this.s.db.command(command, options, function(err, result) {
    if(err) {
      handleCallback(callback, err);
    } else if(result['err'] || result['errmsg']) {
      handleCallback(callback, toError(result));
    } else if(typeof result == 'object' && result['serverPipeline']) {
      handleCallback(callback, null, result['serverPipeline']);
    } else if(typeof result == 'object' && result['stages']) {
      handleCallback(callback, null, result['stages']);
    } else {
      handleCallback(callback, null, result.result);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.bulkWrite"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>bulkWrite (operations, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.bulkWrite)
- description and source-code
```javascript
bulkWrite = function (operations, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {ordered:true};

  if(!Array.isArray(operations)) {
    throw MongoError.create({message: "operations must be an array of documents", driver:true });
  }

  // Execute using callback
  if(typeof callback == 'function') return bulkWrite(self, operations, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    bulkWrite(self, operations, options, function(err, r) {
      if(err && r == null) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.count"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>count (query, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.count)
- description and source-code
```javascript
count = function (query, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 0);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  var queryOption = args.length ? args.shift() || {} : {};
  var optionsOption = args.length ? args.shift() || {} : {};

  // Execute using callback
  if(typeof callback == 'function') return count(self, queryOption, optionsOption, callback);

  // Check if query is empty
  query = query || {};
  options = options || {};

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    count(self, query, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.createIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>createIndex (fieldOrSpec, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.createIndex)
- description and source-code
```javascript
createIndex = function (fieldOrSpec, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  options = args.length ? args.shift() || {} : {};
  options = typeof callback === 'function' ? options : callback;
  options = options == null ? {} : options;

  // Execute using callback
  if(typeof callback == 'function') return createIndex(self, fieldOrSpec, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    createIndex(self, fieldOrSpec, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.createIndexes"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>createIndexes (indexSpecs, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.createIndexes)
- description and source-code
```javascript
createIndexes = function (indexSpecs, callback) {
  var self = this;

  // Execute using callback
  if(typeof callback == 'function') return createIndexes(self, indexSpecs, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    createIndexes(self, indexSpecs, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.deleteMany"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>deleteMany (filter, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.deleteMany)
- description and source-code
```javascript
deleteMany = function (filter, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = shallowClone(options);

  // Add ignoreUndfined
  if(this.s.options.ignoreUndefined) {
    options = shallowClone(options);
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute using callback
  if(typeof callback == 'function') return deleteMany(self, filter, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    deleteMany(self, filter, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.deleteOne"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>deleteOne (filter, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.deleteOne)
- description and source-code
```javascript
deleteOne = function (filter, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = shallowClone(options);

  // Add ignoreUndfined
  if(this.s.options.ignoreUndefined) {
    options = shallowClone(options);
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute using callback
  if(typeof callback == 'function') return deleteOne(self, filter, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    deleteOne(self, filter, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.distinct"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>distinct (key, query, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.distinct)
- description and source-code
```javascript
distinct = function (key, query, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  var queryOption = args.length ? args.shift() || {} : {};
  var optionsOption = args.length ? args.shift() || {} : {};

  // Execute using callback
  if(typeof callback == 'function') return distinct(self, key, queryOption, optionsOption, callback);

  // Ensure the query and options are set
  query = query || {};
  options = options || {};

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    distinct(self, key, query, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.drop"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>drop (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.drop)
- description and source-code
```javascript
drop = function (options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Execute using callback
  if(typeof callback == 'function') return self.s.db.dropCollection(self.s.name, options, callback);
  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.s.db.dropCollection(self.s.name, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.dropAllIndexes"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>dropAllIndexes (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.dropAllIndexes)
- description and source-code
```javascript
dropAllIndexes = function (options, callback) {
  var self = this;

  // Do we have options
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Execute using callback
  if(typeof callback == 'function') return dropIndexes(self, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    dropIndexes(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.dropIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>dropIndex (indexName, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.dropIndex)
- description and source-code
```javascript
dropIndex = function (indexName, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  options = args.length ? args.shift() || {} : {};
  // Run only against primary
  options.readPreference = ReadPreference.PRIMARY;

  // Execute using callback
  if(typeof callback == 'function') return dropIndex(self, indexName, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    dropIndex(self, indexName, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.dropIndexes"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>dropIndexes (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.dropIndexes)
- description and source-code
```javascript
dropIndexes = function (options, callback) {
  var self = this;

  // Do we have options
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Execute using callback
  if(typeof callback == 'function') return dropIndexes(self, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    dropIndexes(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.ensureIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>ensureIndex (fieldOrSpec, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.ensureIndex)
- description and source-code
```javascript
ensureIndex = function (fieldOrSpec, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Execute using callback
  if(typeof callback == 'function') return ensureIndex(self, fieldOrSpec, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    ensureIndex(self, fieldOrSpec, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.find"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>find ()](#apidoc.element.mongoskin.connect.Collection.prototype.find)
- description and source-code
```javascript
find = function () {
  var options
    , args = Array.prototype.slice.call(arguments, 0)
    , has_callback = typeof args[args.length - 1] === 'function'
    , has_weird_callback = typeof args[0] === 'function'
    , callback = has_callback ? args.pop() : (has_weird_callback ? args.shift() : null)
    , len = args.length
    , selector = len >= 1 ? args[0] : {}
    , fields = len >= 2 ? args[1] : undefined;

  if(len === 1 && has_weird_callback) {
    // backwards compat for callback?, options case
    selector = {};
    options = args[0];
  }

  if(len === 2 && fields !== undefined && !Array.isArray(fields)) {
    var fieldKeys = Object.keys(fields);
    var is_option = false;

    for(var i = 0; i < fieldKeys.length; i++) {
      if(testForFields[fieldKeys[i]] != null) {
        is_option = true;
        break;
      }
    }

    if(is_option) {
      options = fields;
      fields = undefined;
    } else {
      options = {};
    }
  } else if(len === 2 && Array.isArray(fields) && !Array.isArray(fields[0])) {
    var newFields = {};
    // Rewrite the array
    for(i = 0; i < fields.length; i++) {
      newFields[fields[i]] = 1;
    }
    // Set the fields
    fields = newFields;
  }

  if(3 === len) {
    options = args[2];
  }

  // Ensure selector is not null
  selector = selector == null ? {} : selector;
  // Validate correctness off the selector
  var object = selector;
  if(Buffer.isBuffer(object)) {
    var object_size = object[0] | object[1] << 8 | object[2] << 16 | object[3] << 24;
    if(object_size != object.length)  {
      var error = new Error("query selector raw message size does not match message header size [" + object.length + "] != [" +
object_size + "]");
      error.name = 'MongoError';
      throw error;
    }
  }

  // Validate correctness of the field selector
  object = fields;
  if(Buffer.isBuffer(object)) {
    object_size = object[0] | object[1] << 8 | object[2] << 16 | object[3] << 24;
    if(object_size != object.length)  {
      error = new Error("query fields raw message size does not match message header size [" + object.length + "] != [" + object_size
 + "]");
      error.name = 'MongoError';
      throw error;
    }
  }

  // Check special case where we are using an objectId
  if(selector != null && selector._bsontype == 'ObjectID') {
    selector = {_id:selector};
  }

  // If it's a serialized fields field we need to just let it through
  // user be warned it better be good
  if(options && options.fields && !(Buffer.isBuffer(options.fields))) {
    fields = {};

    if(Array.isArray(options.fields)) {
      if(!options.fields.length) {
        fields['_id'] = 1;
      } else {
        var l = options.fields.length;

        for (i = 0; i < l; i++) {
          fields[options.fields[i]] = 1;
        }
      }
    } else {
      fields = options.fields;
    }
  }

  if (!options) options = {};

  var newOptions = {};
  // Make a shallow copy of options
  for (var key in options) {
    newOptions[key] = options[key];
  }

  // Unpack options
  newOptions.skip = len > 3 ? args[2] : options.skip ? options.skip : 0;
  newOptions.limit = len > 3 ? args[3] : options.limit ? options.limit : 0;
  newOptions.raw = options.raw != null && typeof options.raw === 'boolean' ? options.raw : this.s.raw;
  newOptions.hint = options.hint != null ? normalizeHintField(options.hint) : this.s.collectionHint;
  newOptions.timeout = len == 5 ? args[4] : typeof options.timeout === 'undefined' ? undefined : options.timeout;
  // // If we have overridden slaveOk otherwise use the default db setting
  newOptions.slaveOk = options.slaveOk != null ? options.slaveOk : this.s.db.slaveOk;

  // Add read preference if needed
  newOptions = getReadPreference(this, newOptions, this.s.db, this);

  // Set slave ok to true if read preference different from primary
  if(newOptions.readPreference != null
    && (newOptions.readPreference != 'primary' || newOptions.readPreference.mode != 'primary')) {
    newOptions.slaveOk = true;
  }

  // Ensure the query is an object
  if(selector != null && typeof selector != 'object') { ...
```
- example usage
```shell
...

Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
...
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.findAndModify"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findAndModify (query, sort, doc, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.findAndModify)
- description and source-code
```javascript
findAndModify = function (query, sort, doc, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  sort = args.length ? args.shift() || [] : [];
  doc = args.length ? args.shift() : null;
  options = args.length ? args.shift() || {} : {};

  // Clone options
  options = shallowClone(options);
  // Force read preference primary
  options.readPreference = ReadPreference.PRIMARY;

  // Execute using callback
  if(typeof callback == 'function') return findAndModify(self, query, sort, doc, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    options = options || {};

    findAndModify(self, query, sort, doc, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.findAndRemove"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findAndRemove (query, sort, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.findAndRemove)
- description and source-code
```javascript
findAndRemove = function (query, sort, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  sort = args.length ? args.shift() || [] : [];
  options = args.length ? args.shift() || {} : {};

  // Execute using callback
  if(typeof callback == 'function') return findAndRemove(self, query, sort, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    findAndRemove(self, query, sort, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.findOne"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findOne ()](#apidoc.element.mongoskin.connect.Collection.prototype.findOne)
- description and source-code
```javascript
findOne = function () {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 0);
  var callback = args.pop();
  if(typeof callback != 'function') args.push(callback);

  // Execute using callback
  if(typeof callback == 'function') return findOne(self, args, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    findOne(self, args, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
...
Model helper:

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article').bind({
    getByAuthor: function(author_id, callback) {
        this.findOne({author_id: author_id}, callback);
    }
});
db.article.getByAuthor(author_id, function(err, article) {
        console.log(article);
});
'''
...
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.findOneAndDelete"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findOneAndDelete (filter, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.findOneAndDelete)
- description and source-code
```javascript
findOneAndDelete = function (filter, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Basic validation
  if(filter == null || typeof filter != 'object') throw toError('filter parameter must be an object');

  // Execute using callback
  if(typeof callback == 'function') return findOneAndDelete(self, filter, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    options = options || {};

    findOneAndDelete(self, filter, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.findOneAndReplace"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findOneAndReplace (filter, replacement, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.findOneAndReplace)
- description and source-code
```javascript
findOneAndReplace = function (filter, replacement, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Basic validation
  if(filter == null || typeof filter != 'object') throw toError('filter parameter must be an object');
  if(replacement == null || typeof replacement != 'object') throw toError('replacement parameter must be an object');

  // Execute using callback
  if(typeof callback == 'function') return findOneAndReplace(self, filter, replacement, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    options = options || {};

    findOneAndReplace(self, filter, replacement, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.findOneAndUpdate"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>findOneAndUpdate (filter, update, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.findOneAndUpdate)
- description and source-code
```javascript
findOneAndUpdate = function (filter, update, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Basic validation
  if(filter == null || typeof filter != 'object') throw toError('filter parameter must be an object');
  if(update == null || typeof update != 'object') throw toError('update parameter must be an object');

  // Execute using callback
  if(typeof callback == 'function') return findOneAndUpdate(self, filter, update, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    options = options || {};

    findOneAndUpdate(self, filter, update, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.geoHaystackSearch"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>geoHaystackSearch (x, y, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.geoHaystackSearch)
- description and source-code
```javascript
geoHaystackSearch = function (x, y, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 2);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  // Fetch all commands
  options = args.length ? args.shift() || {} : {};

  // Execute using callback
  if(typeof callback == 'function') return geoHaystackSearch(self, x, y, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    geoHaystackSearch(self, x, y, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.geoNear"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>geoNear (x, y, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.geoNear)
- description and source-code
```javascript
geoNear = function (x, y, options, callback) {
  var self = this;
  var point = typeof(x) == 'object' && x
    , args = Array.prototype.slice.call(arguments, point?1:2);

  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  // Fetch all commands
  options = args.length ? args.shift() || {} : {};

  // Execute using callback
  if(typeof callback == 'function') return geoNear(self, x, y, point, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    geoNear(self, x, y, point, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.group"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>group (keys, condition, initial, reduce, finalize, command, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.group)
- description and source-code
```javascript
group = function (keys, condition, initial, reduce, finalize, command, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 3);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  // Fetch all commands
  reduce = args.length ? args.shift() : null;
  finalize = args.length ? args.shift() : null;
  command = args.length ? args.shift() : null;
  options = args.length ? args.shift() || {} : {};

  // Make sure we are backward compatible
  if(!(typeof finalize == 'function')) {
    command = finalize;
    finalize = null;
  }

  if (!Array.isArray(keys) && keys instanceof Object && typeof(keys) !== 'function' && !(keys._bsontype == 'Code')) {
    keys = Object.keys(keys);
  }

  if(typeof reduce === 'function') {
    reduce = reduce.toString();
  }

  if(typeof finalize === 'function') {
    finalize = finalize.toString();
  }

  // Set up the command as default
  command = command == null ? true : command;

  // Execute using callback
  if(typeof callback == 'function') return group(self, keys, condition, initial, reduce, finalize, command, options, callback);
  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    group(self, keys, condition, initial, reduce, finalize, command, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.indexExists"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>indexExists (indexes, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.indexExists)
- description and source-code
```javascript
indexExists = function (indexes, callback) {
  var self = this;

  // Execute using callback
  if(typeof callback == 'function') return indexExists(self, indexes, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    indexExists(self, indexes, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.indexInformation"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>indexInformation (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.indexInformation)
- description and source-code
```javascript
indexInformation = function (options, callback) {
  var self = this;
  // Unpack calls
  var args = Array.prototype.slice.call(arguments, 0);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  options = args.length ? args.shift() || {} : {};

  // Execute using callback
  if(typeof callback == 'function') return indexInformation(self, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    indexInformation(self, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.indexes"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>indexes (callback)](#apidoc.element.mongoskin.connect.Collection.prototype.indexes)
- description and source-code
```javascript
indexes = function (callback) {
  var self = this;
  // Execute using callback
  if(typeof callback == 'function') return indexes(self, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    indexes(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.initializeOrderedBulkOp"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>initializeOrderedBulkOp (options)](#apidoc.element.mongoskin.connect.Collection.prototype.initializeOrderedBulkOp)
- description and source-code
```javascript
initializeOrderedBulkOp = function (options) {
  options = options || {};
  options.promiseLibrary = this.s.promiseLibrary;
  return ordered(this.s.topology, this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.initializeUnorderedBulkOp"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>initializeUnorderedBulkOp (options)](#apidoc.element.mongoskin.connect.Collection.prototype.initializeUnorderedBulkOp)
- description and source-code
```javascript
initializeUnorderedBulkOp = function (options) {
  options = options || {};
  options.promiseLibrary = this.s.promiseLibrary;
  return unordered(this.s.topology, this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.insert"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>insert (docs, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.insert)
- description and source-code
```javascript
insert = function (docs, options, callback) {
  if(typeof options == 'function') callback = options, options = {};
  options = options || {ordered:false};
  docs = !Array.isArray(docs) ? [docs] : docs;

  if(options.keepGoing == true) {
    options.ordered = false;
  }

  return this.insertMany(docs, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.insertMany"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>insertMany (docs, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.insertMany)
- description and source-code
```javascript
insertMany = function (docs, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {ordered:true};
  if(!Array.isArray(docs) && typeof callback == 'function') {
    return callback(MongoError.create({message: 'docs parameter must be an array of documents', driver:true }));
  } else if(!Array.isArray(docs)) {
    return new this.s.promiseLibrary(function(resolve, reject) {
      reject(MongoError.create({message: 'docs parameter must be an array of documents', driver:true }));
    });
  }

  // Get the write concern options
  if(typeof options.checkKeys != 'boolean') {
    options.checkKeys = true;
  }

  // If keep going set unordered
  options['serializeFunctions'] = options['serializeFunctions'] || self.s.serializeFunctions;

  // Set up the force server object id
  var forceServerObjectId = typeof options.forceServerObjectId == 'boolean'
    ? options.forceServerObjectId : self.s.db.options.forceServerObjectId;

  // Do we want to force the server to assign the _id key
  if(forceServerObjectId !== true) {
    // Add _id if not specified
    for(var i = 0; i < docs.length; i++) {
      if(docs[i]._id == null) docs[i]._id = self.s.pkFactory.createPk();
    }
  }

  // Generate the bulk write operations
  var operations = [{
    insertMany: docs
  }];

  // Execute using callback
  if(typeof callback == 'function') return bulkWrite(self, operations, options, function(err, r) {
    if(err) return callback(err, r);
    callback(null, mapInserManyResults(docs, r));
  });

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    bulkWrite(self, operations, options, function(err, r) {
      if(err) return reject(err);
      resolve(mapInserManyResults(docs, r));
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.insertOne"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>insertOne (doc, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.insertOne)
- description and source-code
```javascript
insertOne = function (doc, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};
  if(Array.isArray(doc) && typeof callback == 'function') {
    return callback(MongoError.create({message: 'doc parameter must be an object', driver:true }));
  } else if(Array.isArray(doc)) {
    return new this.s.promiseLibrary(function(resolve, reject) {
      reject(MongoError.create({message: 'doc parameter must be an object', driver:true }));
    });
  }

  // Add ignoreUndfined
  if(this.s.options.ignoreUndefined) {
    options = shallowClone(options);
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute using callback
  if(typeof callback == 'function') return insertOne(self, doc, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    insertOne(self, doc, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.isCapped"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>isCapped (callback)](#apidoc.element.mongoskin.connect.Collection.prototype.isCapped)
- description and source-code
```javascript
isCapped = function (callback) {
  var self = this;

  // Execute using callback
  if(typeof callback == 'function') return isCapped(self, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    isCapped(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.listIndexes"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>listIndexes (options)](#apidoc.element.mongoskin.connect.Collection.prototype.listIndexes)
- description and source-code
```javascript
listIndexes = function (options) {
  options = options || {};
  // Clone the options
  options = shallowClone(options);
  // Determine the read preference in the options.
  options = getReadPreference(this, options, this.s.db, this);
  // Set the CommandCursor constructor
  options.cursorFactory = CommandCursor;
  // Set the promiseLibrary
  options.promiseLibrary = this.s.promiseLibrary;

  if(!this.s.topology.capabilities()) {
    throw new MongoError('cannot connect to server');
  }

  // We have a list collections command
  if(this.s.topology.capabilities().hasListIndexesCommand) {
    // Cursor options
    var cursor = options.batchSize ? {batchSize: options.batchSize} : {}
    // Build the command
    var command = { listIndexes: this.s.name, cursor: cursor };
    // Execute the cursor
    cursor = this.s.topology.cursor(f('%s.$cmd', this.s.dbName), command, options);
    // Do we have a readPreference, apply it
    if(options.readPreference) cursor.setReadPreference(options.readPreference);
    // Return the cursor
    return cursor;
  }

  // Get the namespace
  var ns = f('%s.system.indexes', this.s.dbName);
  // Get the query
  cursor = this.s.topology.cursor(ns, {find: ns, query: {ns: this.s.namespace}}, options);
  // Do we have a readPreference, apply it
  if(options.readPreference) cursor.setReadPreference(options.readPreference);
  // Set the passed in batch size if one was provided
  if(options.batchSize) cursor = cursor.batchSize(options.batchSize);
  // Return the cursor
  return cursor;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.mapReduce"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>mapReduce (map, reduce, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.mapReduce)
- description and source-code
```javascript
mapReduce = function (map, reduce, options, callback) {
  var self = this;
  if('function' === typeof options) callback = options, options = {};
  // Out must allways be defined (make sure we don't break weirdly on pre 1.8+ servers)
  if(null == options.out) {
    throw new Error("the out option parameter must be defined, see mongodb docs for possible values");
  }

  if('function' === typeof map) {
    map = map.toString();
  }

  if('function' === typeof reduce) {
    reduce = reduce.toString();
  }

  if('function' === typeof options.finalize) {
    options.finalize = options.finalize.toString();
  }

  // Execute using callback
  if(typeof callback == 'function') return mapReduce(self, map, reduce, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    mapReduce(self, map, reduce, options, function(err, r, r1) {
      if(err) return reject(err);
      if(!r1) return resolve(r);
      resolve({results: r, stats: r1});
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.options"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>options (callback)](#apidoc.element.mongoskin.connect.Collection.prototype.options)
- description and source-code
```javascript
options = function (callback) {
  var self = this;

  // Execute using callback
  if(typeof callback == 'function') return options(self, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    options(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.parallelCollectionScan"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>parallelCollectionScan (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.parallelCollectionScan)
- description and source-code
```javascript
parallelCollectionScan = function (options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {numCursors: 1};
  // Set number of cursors to 1
  options.numCursors = options.numCursors || 1;
  options.batchSize = options.batchSize || 1000;

  options = shallowClone(options);
  // Ensure we have the right read preference inheritance
  options = getReadPreference(this, options, this.s.db, this);

  // Add a promiseLibrary
  options.promiseLibrary = this.s.promiseLibrary;

  // Execute using callback
  if(typeof callback == 'function') return parallelCollectionScan(self, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    parallelCollectionScan(self, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.reIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>reIndex (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.reIndex)
- description and source-code
```javascript
reIndex = function (options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Execute using callback
  if(typeof callback == 'function') return reIndex(self, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    reIndex(self, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.remove"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>remove (selector, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.remove)
- description and source-code
```javascript
remove = function (selector, options, callback) {
  var self = this;

  // Add ignoreUndfined
  if(this.s.options.ignoreUndefined) {
    options = shallowClone(options);
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute using callback
  if(typeof callback == 'function') return removeDocuments(self, selector, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    removeDocuments(self, selector, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
...
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native

### Removed API from mongoskin 1.3.20
...
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.removeMany"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>removeMany (filter, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.removeMany)
- description and source-code
```javascript
removeMany = function (filter, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = shallowClone(options);

  // Add ignoreUndfined
  if(this.s.options.ignoreUndefined) {
    options = shallowClone(options);
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute using callback
  if(typeof callback == 'function') return deleteMany(self, filter, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    deleteMany(self, filter, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.removeOne"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>removeOne (filter, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.removeOne)
- description and source-code
```javascript
removeOne = function (filter, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = shallowClone(options);

  // Add ignoreUndfined
  if(this.s.options.ignoreUndefined) {
    options = shallowClone(options);
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute using callback
  if(typeof callback == 'function') return deleteOne(self, filter, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    deleteOne(self, filter, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.rename"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>rename (newName, opt, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.rename)
- description and source-code
```javascript
rename = function (newName, opt, callback) {
  var self = this;
  if(typeof opt == 'function') callback = opt, opt = {};
  opt = assign({}, opt, {readPreference: ReadPreference.PRIMARY});

  // Execute using callback
  if(typeof callback == 'function') return rename(self, newName, opt, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    rename(self, newName, opt, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.replaceOne"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>replaceOne (filter, doc, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.replaceOne)
- description and source-code
```javascript
replaceOne = function (filter, doc, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = shallowClone(options)

  // Add ignoreUndfined
  if(this.s.options.ignoreUndefined) {
    options = shallowClone(options);
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute using callback
  if(typeof callback == 'function') return replaceOne(self, filter, doc, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    replaceOne(self, filter, doc, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.save"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>save (doc, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.save)
- description and source-code
```javascript
save = function (doc, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Add ignoreUndfined
  if(this.s.options.ignoreUndefined) {
    options = shallowClone(options);
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute using callback
  if(typeof callback == 'function') return save(self, doc, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    save(self, doc, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.stats"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>stats (options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.stats)
- description and source-code
```javascript
stats = function (options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 0);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  // Fetch all commands
  options = args.length ? args.shift() || {} : {};

  // Execute using callback
  if(typeof callback == 'function') return stats(self, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    stats(self, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.update"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>update (selector, document, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.update)
- description and source-code
```javascript
update = function (selector, document, options, callback) {
  var self = this;

  // Add ignoreUndfined
  if(this.s.options.ignoreUndefined) {
    options = shallowClone(options);
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute using callback
  if(typeof callback == 'function') return updateDocuments(self, selector, document, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    updateDocuments(self, selector, document, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
...
### db.gridStore(...)
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
### collection.findById(id, ...)
alias 'collection.find({_id: toObjectID(id)}, ...)'
### collection.updateById(id, ...)
alias 'collection.update({_id: toObjectID(id)}, ...)'
### collection.removeById(id, ...)
alias 'collection.remove({_id: toObjectID(id)}, ...)'

## NOTE!! mongoskin API change from 1.3.20

Since node-mongodb-native has change a lot of API, mongoskin redesign from 1.3.20. The version number keep same with node-mongodb
-native. And the API appearence is also keep same with node-mongodb-native
...
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.updateMany"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>updateMany (filter, update, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.updateMany)
- description and source-code
```javascript
updateMany = function (filter, update, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = shallowClone(options)

  // Add ignoreUndfined
  if(this.s.options.ignoreUndefined) {
    options = shallowClone(options);
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute using callback
  if(typeof callback == 'function') return updateMany(self, filter, update, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    updateMany(self, filter, update, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Collection.prototype.updateOne"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Collection.prototype.</span>updateOne (filter, update, options, callback)](#apidoc.element.mongoskin.connect.Collection.prototype.updateOne)
- description and source-code
```javascript
updateOne = function (filter, update, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = shallowClone(options)

  // Add ignoreUndfined
  if(this.s.options.ignoreUndefined) {
    options = shallowClone(options);
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute using callback
  if(typeof callback == 'function') return updateOne(self, filter, update, options, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    updateOne(self, filter, update, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.connect.Cursor"></a>[module mongoskin.connect.Cursor](#apidoc.module.mongoskin.connect.Cursor)

#### <a name="apidoc.element.mongoskin.connect.Cursor.Cursor"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Cursor (bson, ns, cmd, options, topology, topologyOptions)](#apidoc.element.mongoskin.connect.Cursor.Cursor)
- description and source-code
```javascript
Cursor = function (bson, ns, cmd, options, topology, topologyOptions) {
  CoreCursor.apply(this, Array.prototype.slice.call(arguments, 0));
  var self = this;
  var state = Cursor.INIT;
  var streamOptions = {};

  // Tailable cursor options
  var numberOfRetries = options.numberOfRetries || 5;
  var tailableRetryInterval = options.tailableRetryInterval || 500;
  var currentNumberOfRetries = numberOfRetries;

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Set up
  Readable.call(this, {objectMode: true});

  // Internal cursor state
  this.s = {
    // Tailable cursor options
      numberOfRetries: numberOfRetries
    , tailableRetryInterval: tailableRetryInterval
    , currentNumberOfRetries: currentNumberOfRetries
    // State
    , state: state
    // Stream options
    , streamOptions: streamOptions
    // BSON
    , bson: bson
    // Namespace
    , ns: ns
    // Command
    , cmd: cmd
    // Options
    , options: options
    // Topology
    , topology: topology
    // Topology options
    , topologyOptions: topologyOptions
    // Promise library
    , promiseLibrary: promiseLibrary
    // Current doc
    , currentDoc: null
  }

  // Translate correctly
  if(self.s.options.noCursorTimeout == true) {
    self.addCursorFlag('noCursorTimeout', true);
  }

  // Set the sort value
  this.sortValue = self.s.cmd.sort;

  // Get the batchSize
  var batchSize = cmd.cursor && cmd.cursor.batchSize
    ? cmd.cursor && cmd.cursor.batchSize
    : (options.cursor && options.cursor.batchSize ? options.cursor.batchSize : 1000);

  // Set the batchSize
  this.setCursorBatchSize(batchSize);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.super_"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.</span>super_ (options)](#apidoc.element.mongoskin.connect.Cursor.super_)
- description and source-code
```javascript
function Readable(options) {
  if (!(this instanceof Readable))
    return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  if (options && typeof options.read === 'function')
    this._read = options.read;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.connect.Cursor.prototype"></a>[module mongoskin.connect.Cursor.prototype](#apidoc.module.mongoskin.connect.Cursor.prototype)

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype._find"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>_find (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype._find)
- description and source-code
```javascript
_find = function (callback) {
  var self = this;

  if(self.logger.isDebug()) {
    self.logger.debug(f('issue initial query [%s] with flags [%s]'
      , JSON.stringify(self.cmd)
      , JSON.stringify(self.query)));
  }

  var queryCallback = function(err, r) {
    if(err) return callback(err);

    // Get the raw message
    var result = r.message;

    // Query failure bit set
    if(result.queryFailure) {
      return callback(MongoError.create(result.documents[0]), null);
    }

    // Check if we have a command cursor
    if(Array.isArray(result.documents) && result.documents.length == 1
      && (!self.cmd.find || (self.cmd.find && self.cmd.virtual == false))
      && (result.documents[0].cursor != 'string'
        || result.documents[0]['$err']
        || result.documents[0]['errmsg']
        || Array.isArray(result.documents[0].result))
      ) {

      // We have a an error document return the error
      if(result.documents[0]['$err']
        || result.documents[0]['errmsg']) {
        return callback(MongoError.create(result.documents[0]), null);
      }

      // We have a cursor document
      if(result.documents[0].cursor != null
        && typeof result.documents[0].cursor != 'string') {
          var id = result.documents[0].cursor.id;
          // If we have a namespace change set the new namespace for getmores
          if(result.documents[0].cursor.ns) {
            self.ns = result.documents[0].cursor.ns;
          }
          // Promote id to long if needed
          self.cursorState.cursorId = typeof id == 'number' ? Long.fromNumber(id) : id;
          self.cursorState.lastCursorId = self.cursorState.cursorId;
          // If we have a firstBatch set it
          if(Array.isArray(result.documents[0].cursor.firstBatch)) {
            self.cursorState.documents = result.documents[0].cursor.firstBatch;//.reverse();
          }

          // Return after processing command cursor
          return callback(null, null);
      }

      if(Array.isArray(result.documents[0].result)) {
        self.cursorState.documents = result.documents[0].result;
        self.cursorState.cursorId = Long.ZERO;
        return callback(null, null);
      }
    }

    // Otherwise fall back to regular find path
    self.cursorState.cursorId = result.cursorId;
    self.cursorState.documents = result.documents;
    self.cursorState.lastCursorId = result.cursorId;

    // Transform the results with passed in transformation method if provided
    if(self.cursorState.transforms && typeof self.cursorState.transforms.query == 'function') {
      self.cursorState.documents = self.cursorState.transforms.query(result);
    }

    // Return callback
    callback(null, null);
  }

  // Options passed to the pool
  var queryOptions = {};

  // If we have a raw query decorate the function
  if(self.options.raw || self.cmd.raw) {
    // queryCallback.raw = self.options.raw || self.cmd.raw;
    queryOptions.raw = self.options.raw || self.cmd.raw;
  }

  // Do we have documentsReturnedIn set on the query
  if(typeof self.query.documentsReturnedIn == 'string') {
    // queryCallback.documentsReturnedIn = self.query.documentsReturnedIn;
    queryOptions.documentsReturnedIn = self.query.documentsReturnedIn;
  }

  // Add promote Long value if defined
  if(typeof self.cursorState.promoteLongs == 'boolean') {
    queryOptions.promoteLongs = self.cursorState.promoteLongs;
  }

  // Add promote values if defined
  if(typeof self.cursorState.promoteValues == 'boolean') {
    queryOptions.promoteValues = self.cursorState.promoteValues;
  }

  // Add promote values if defined
  if(typeof self.cursorState.promoteBuffers == 'boolean') {
    queryOptions.promoteBuffers = self.cursorState.promoteBuffers;
  }
  // Write the initial command out
  self.server.s.pool.write(self.query, queryOptions, queryCallback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype._getmore"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>_getmore (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype._getmore)
- description and source-code
```javascript
_getmore = function (callback) {
  if(this.logger.isDebug()) this.logger.debug(f('schedule getMore call for query [%s]', JSON.stringify(this.query)))
  // Determine if it's a raw query
  var raw = this.options.raw || this.cmd.raw;

  // Set the current batchSize
  var batchSize = this.cursorState.batchSize;
  if(this.cursorState.limit > 0
    && ((this.cursorState.currentLimit + batchSize) > this.cursorState.limit)) {
    batchSize = this.cursorState.limit - this.cursorState.currentLimit;
  }

  // Default pool
  var pool = this.server.s.pool;

  // We have a wire protocol handler
  this.server.wireProtocolHandler.getMore(this.bson, this.ns, this.cursorState, batchSize, raw, pool, this.options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype._killcursor"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>_killcursor (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype._killcursor)
- description and source-code
```javascript
_killcursor = function (callback) {
  // Set cursor to dead
  this.cursorState.dead = true;
  this.cursorState.killed = true;
  // Remove documents
  this.cursorState.documents = [];

  // If no cursor id just return
  if(this.cursorState.cursorId == null || this.cursorState.cursorId.isZero() || this.cursorState.init == false) {
    if(callback) callback(null, null);
    return;
  }

  // Default pool
  var pool = this.server.s.pool;
  // Execute command
  this.server.wireProtocolHandler.killCursor(this.bson, this.ns, this.cursorState.cursorId, pool, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype._next"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>_next (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype._next)
- description and source-code
```javascript
_next = function (callback) {
  nextFunction(this, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype._read"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>_read ()](#apidoc.element.mongoskin.connect.Cursor.prototype._read)
- description and source-code
```javascript
_read = function () {
  var self = this;
  if(self.s.state == Cursor.CLOSED || self.isDead()) {
    return self.push(null);
  }

  // Get the next item
  self.nextObject(function(err, result) {
    if(err) {
      if(self.listeners('error') && self.listeners('error').length > 0) {
        self.emit('error', err);
      }
      if(!self.isDead()) self.close();

      // Emit end event
      self.emit('end');
      return self.emit('finish');
    }

    // If we provided a transformation method
    if(typeof self.s.streamOptions.transform == 'function' && result != null) {
      return self.push(self.s.streamOptions.transform(result));
    }

    // If we provided a map function
    if(self.cursorState.transforms && typeof self.cursorState.transforms.doc == 'function' && result != null) {
      return self.push(self.cursorState.transforms.doc(result));
    }

    // Return the result
    self.push(result);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.addCursorFlag"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>addCursorFlag (flag, value)](#apidoc.element.mongoskin.connect.Cursor.prototype.addCursorFlag)
- description and source-code
```javascript
addCursorFlag = function (flag, value) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  if(flags.indexOf(flag) == -1) throw MongoError.create({message: f("flag %s not a supported flag %s", flag, flags), driver:true
 });
  if(typeof value != 'boolean') throw MongoError.create({message: f("flag %s must be a boolean value", flag), driver:true});
  this.s.cmd[flag] = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.addQueryModifier"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>addQueryModifier (name, value)](#apidoc.element.mongoskin.connect.Cursor.prototype.addQueryModifier)
- description and source-code
```javascript
addQueryModifier = function (name, value) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  if(name[0] != '$') throw MongoError.create({message: f("%s is not a valid query modifier"), driver:true});
  // Strip of the $
  var field = name.substr(1);
  // Set on the command
  this.s.cmd[field] = value;
  // Deal with the special case for sort
  if(field == 'orderby') this.s.cmd.sort = this.s.cmd[field];
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.batchSize"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>batchSize (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.batchSize)
- description and source-code
```javascript
batchSize = function (value) {
  if(this.s.options.tailable) throw MongoError.create({message: "Tailable cursor doesn't support batchSize", driver:true});
  if(this.s.state == Cursor.CLOSED || this.isDead()) throw MongoError.create({message: "Cursor is closed", driver:true});
  if(typeof value != 'number') throw MongoError.create({message: "batchSize requires an integer", driver:true});
  this.s.cmd.batchSize = value;
  this.setCursorBatchSize(value);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.bufferedCount"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>bufferedCount ()](#apidoc.element.mongoskin.connect.Cursor.prototype.bufferedCount)
- description and source-code
```javascript
bufferedCount = function () {
  return this.cursorState.documents.length - this.cursorState.cursorIndex;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.clone"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>clone ()](#apidoc.element.mongoskin.connect.Cursor.prototype.clone)
- description and source-code
```javascript
clone = function () {
  return this.topology.cursor(this.ns, this.cmd, this.options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>close (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.close)
- description and source-code
```javascript
close = function (callback) {
  this.s.state = Cursor.CLOSED;
  // Kill the cursor
  this.kill();
  // Emit the close event for the cursor
  this.emit('close');
  // Callback if provided
  if(typeof callback == 'function') return handleCallback(callback, null, this);
  // Return a Promise
  return new this.s.promiseLibrary(function(resolve) {
    resolve();
  });
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.collation"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>collation (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.collation)
- description and source-code
```javascript
collation = function (value) {
  this.s.cmd.collation = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.comment"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>comment (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.comment)
- description and source-code
```javascript
comment = function (value) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.comment = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.count"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>count (applySkipLimit, opts, callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.count)
- description and source-code
```javascript
count = function (applySkipLimit, opts, callback) {
  var self = this;
  if(self.s.cmd.query == null) throw MongoError.create({message: "count can only be used with find command", driver:true});
  if(typeof opts == 'function') callback = opts, opts = {};
  opts = opts || {};

  // Execute using callback
  if(typeof callback == 'function') return count(self, applySkipLimit, opts, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    count(self, applySkipLimit, opts, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.cursorBatchSize"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>cursorBatchSize ()](#apidoc.element.mongoskin.connect.Cursor.prototype.cursorBatchSize)
- description and source-code
```javascript
cursorBatchSize = function () {
  return this.cursorState.batchSize;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.cursorLimit"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>cursorLimit ()](#apidoc.element.mongoskin.connect.Cursor.prototype.cursorLimit)
- description and source-code
```javascript
cursorLimit = function () {
  return this.cursorState.limit;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.cursorSkip"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>cursorSkip ()](#apidoc.element.mongoskin.connect.Cursor.prototype.cursorSkip)
- description and source-code
```javascript
cursorSkip = function () {
  return this.cursorState.skip;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.destroy"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>destroy (err)](#apidoc.element.mongoskin.connect.Cursor.prototype.destroy)
- description and source-code
```javascript
destroy = function (err) {
  if(err) this.emit('error', err);
  this.pause();
  this.close();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.each"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>each (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.each)
- description and source-code
```javascript
each = function (callback) {
  // Rewind cursor state
  this.rewind();
  // Set current cursor to INIT
  this.s.state = Cursor.INIT;
  // Run the query
  _each(this, callback);
}
```
- example usage
```shell
...
   cursor.toArray(fn);
 };
 this.find.apply(this, args);
 return this;
};

/**
* find and cursor.each(fn).
*
* @param {Object} [query]
* @param {Object} [options]
* @param {Function(err, item)} eachCallback
* @return {SkinCollection} this
* @api public
*/
...
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.explain"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>explain (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.explain)
- description and source-code
```javascript
explain = function (callback) {
  var self = this;
  this.s.cmd.explain = true;

  // Do we have a readConcern
  if(this.s.cmd.readConcern) {
    delete this.s.cmd['readConcern'];
  }

  // Execute using callback
  if(typeof callback == 'function') return this._next(callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self._next(function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.filter"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>filter (filter)](#apidoc.element.mongoskin.connect.Cursor.prototype.filter)
- description and source-code
```javascript
filter = function (filter) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.query = filter;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.forEach"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>forEach (iterator, callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.forEach)
- description and source-code
```javascript
forEach = function (iterator, callback) {
  this.each(function(err, doc){
    if(err) { callback(err); return false; }
    if(doc != null) { iterator(doc); return true; }
    if(doc == null && callback) {
      var internalCallback = callback;
      callback = null;
      internalCallback(null);
      return false;
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.hasNext"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>hasNext (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.hasNext)
- description and source-code
```javascript
hasNext = function (callback) {
  var self = this;

  // Execute using callback
  if(typeof callback == 'function') {
    if(self.s.currentDoc){
      return callback(null, true);
    } else {
      return nextObject(self, function(err, doc) {
        if(!doc) return callback(null, false);
        self.s.currentDoc = doc;
        callback(null, true);
      });
    }
  }

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    if(self.s.currentDoc){
      resolve(true);
    } else {
      nextObject(self, function(err, doc) {
        if(self.s.state == Cursor.CLOSED || self.isDead()) return resolve(false);
        if(err) return reject(err);
        if(!doc) return resolve(false);
        self.s.currentDoc = doc;
        resolve(true);
      });
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.hint"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>hint (hint)](#apidoc.element.mongoskin.connect.Cursor.prototype.hint)
- description and source-code
```javascript
hint = function (hint) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.hint = hint;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.isClosed"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>isClosed ()](#apidoc.element.mongoskin.connect.Cursor.prototype.isClosed)
- description and source-code
```javascript
isClosed = function () {
  return this.isDead();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.isDead"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>isDead ()](#apidoc.element.mongoskin.connect.Cursor.prototype.isDead)
- description and source-code
```javascript
isDead = function () {
  return this.cursorState.dead == true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.isKilled"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>isKilled ()](#apidoc.element.mongoskin.connect.Cursor.prototype.isKilled)
- description and source-code
```javascript
isKilled = function () {
  return this.cursorState.killed == true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.isNotified"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>isNotified ()](#apidoc.element.mongoskin.connect.Cursor.prototype.isNotified)
- description and source-code
```javascript
isNotified = function () {
  return this.cursorState.notified == true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.kill"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>kill (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.kill)
- description and source-code
```javascript
kill = function (callback) {
  this._killcursor(callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.limit"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>limit (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.limit)
- description and source-code
```javascript
limit = function (value) {
  if(this.s.options.tailable) throw MongoError.create({message: "Tailable cursor doesn't support limit", driver:true});
  if(this.s.state == Cursor.OPEN || this.s.state == Cursor.CLOSED || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  if(typeof value != 'number') throw MongoError.create({message: "limit requires an integer", driver:true});
  this.s.cmd.limit = value;
  // this.cursorLimit = value;
  this.setCursorLimit(value);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.map"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>map (transform)](#apidoc.element.mongoskin.connect.Cursor.prototype.map)
- description and source-code
```javascript
map = function (transform) {
  this.cursorState.transforms = { doc: transform };
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.max"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>max (max)](#apidoc.element.mongoskin.connect.Cursor.prototype.max)
- description and source-code
```javascript
max = function (max) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.max = max;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.maxAwaitTimeMS"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>maxAwaitTimeMS (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.maxAwaitTimeMS)
- description and source-code
```javascript
maxAwaitTimeMS = function (value) {
  if(typeof value != 'number') throw MongoError.create({message: "maxAwaitTimeMS must be a number", driver:true});
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.maxAwaitTimeMS = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.maxScan"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>maxScan (maxScan)](#apidoc.element.mongoskin.connect.Cursor.prototype.maxScan)
- description and source-code
```javascript
maxScan = function (maxScan) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.maxScan = maxScan;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.maxTimeMS"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>maxTimeMS (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.maxTimeMS)
- description and source-code
```javascript
maxTimeMS = function (value) {
  if(typeof value != 'number') throw MongoError.create({message: "maxTimeMS must be a number", driver:true});
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.maxTimeMS = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.maxTimeMs"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>maxTimeMs (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.maxTimeMs)
- description and source-code
```javascript
maxTimeMs = function (value) {
  if(typeof value != 'number') throw MongoError.create({message: "maxTimeMS must be a number", driver:true});
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.maxTimeMS = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.min"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>min (min)](#apidoc.element.mongoskin.connect.Cursor.prototype.min)
- description and source-code
```javascript
min = function (min) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.min = min;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.next"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>next (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.next)
- description and source-code
```javascript
next = function (callback) {
  var self = this;

  // Execute using callback
  if(typeof callback == 'function') {
    // Return the currentDoc if someone called hasNext first
    if(self.s.currentDoc) {
      var doc = self.s.currentDoc;
      self.s.currentDoc = null;
      return callback(null, doc);
    }

    // Return the next object
    return nextObject(self, callback)
  }

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    // Return the currentDoc if someone called hasNext first
    if(self.s.currentDoc) {
      var doc = self.s.currentDoc;
      self.s.currentDoc = null;
      return resolve(doc);
    }

    nextObject(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.nextObject"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>nextObject (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.nextObject)
- description and source-code
```javascript
nextObject = function (callback) {
  var self = this;

  // Execute using callback
  if(typeof callback == 'function') {
    // Return the currentDoc if someone called hasNext first
    if(self.s.currentDoc) {
      var doc = self.s.currentDoc;
      self.s.currentDoc = null;
      return callback(null, doc);
    }

    // Return the next object
    return nextObject(self, callback)
  }

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    // Return the currentDoc if someone called hasNext first
    if(self.s.currentDoc) {
      var doc = self.s.currentDoc;
      self.s.currentDoc = null;
      return resolve(doc);
    }

    nextObject(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.project"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>project (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.project)
- description and source-code
```javascript
project = function (value) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.fields = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.readBufferedDocuments"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>readBufferedDocuments (number)](#apidoc.element.mongoskin.connect.Cursor.prototype.readBufferedDocuments)
- description and source-code
```javascript
readBufferedDocuments = function (number) {
  var unreadDocumentsLength = this.cursorState.documents.length - this.cursorState.cursorIndex;
  var length = number < unreadDocumentsLength ? number : unreadDocumentsLength;
  var elements = this.cursorState.documents.slice(this.cursorState.cursorIndex, this.cursorState.cursorIndex + length);

  // Transform the doc with passed in transformation method if provided
  if(this.cursorState.transforms && typeof this.cursorState.transforms.doc == 'function') {
    // Transform all the elements
    for(var i = 0; i < elements.length; i++) {
      elements[i] = this.cursorState.transforms.doc(elements[i]);
    }
  }

  // Ensure we do not return any more documents than the limit imposed
  // Just return the number of elements up to the limit
  if(this.cursorState.limit > 0 && (this.cursorState.currentLimit + elements.length) > this.cursorState.limit) {
    elements = elements.slice(0, (this.cursorState.limit - this.cursorState.currentLimit));
    this.kill();
  }

  // Adjust current limit
  this.cursorState.currentLimit = this.cursorState.currentLimit + elements.length;
  this.cursorState.cursorIndex = this.cursorState.cursorIndex + elements.length;

  // Return elements
  return elements;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.returnKey"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>returnKey (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.returnKey)
- description and source-code
```javascript
returnKey = function (value) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.returnKey = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.rewind"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>rewind ()](#apidoc.element.mongoskin.connect.Cursor.prototype.rewind)
- description and source-code
```javascript
rewind = function () {
  if(this.cursorState.init) {
    if(!this.cursorState.dead) {
      this.kill();
    }

    this.cursorState.currentLimit = 0;
    this.cursorState.init = false;
    this.cursorState.dead = false;
    this.cursorState.killed = false;
    this.cursorState.notified = false;
    this.cursorState.documents = [];
    this.cursorState.cursorId = null;
    this.cursorState.cursorIndex = 0;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.setCursorBatchSize"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>setCursorBatchSize (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.setCursorBatchSize)
- description and source-code
```javascript
setCursorBatchSize = function (value) {
  this.cursorState.batchSize = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.setCursorLimit"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>setCursorLimit (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.setCursorLimit)
- description and source-code
```javascript
setCursorLimit = function (value) {
  this.cursorState.limit = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.setCursorOption"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>setCursorOption (field, value)](#apidoc.element.mongoskin.connect.Cursor.prototype.setCursorOption)
- description and source-code
```javascript
setCursorOption = function (field, value) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  if(fields.indexOf(field) == -1) throw MongoError.create({message: f("option %s not a supported option %s", field, fields), driver
:true });
  this.s[field] = value;
  if(field == 'numberOfRetries')
    this.s.currentNumberOfRetries = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.setCursorSkip"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>setCursorSkip (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.setCursorSkip)
- description and source-code
```javascript
setCursorSkip = function (value) {
  this.cursorState.skip = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.setReadPreference"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>setReadPreference (r)](#apidoc.element.mongoskin.connect.Cursor.prototype.setReadPreference)
- description and source-code
```javascript
setReadPreference = function (r) {
  if(this.s.state != Cursor.INIT) throw MongoError.create({message: 'cannot change cursor readPreference after cursor has been accessed
', driver:true});
  if(r instanceof ReadPreference) {
    this.s.options.readPreference = new CoreReadPreference(r.mode, r.tags, {maxStalenessSeconds: r.maxStalenessSeconds});
  } else if(typeof r == 'string'){
    this.s.options.readPreference = new CoreReadPreference(r);
  } else if(r instanceof CoreReadPreference) {
    this.s.options.readPreference = r;
  }

  return this;
}
```
- example usage
```shell
...
        new Server('localhost', 30000),
        new Server('localhost', 30001),
        new Server('localhost', 30002),
]);

var db = new Db('integration_test_', replSet, {w:0, native_parser: (process.env['TEST_NATIVE'] != null)});
// no need open and on('fullsetup', ...)
db.collection('myconnection').find().setReadPreference(ReadPreference.SECONDARY).toArray(function(err, items) {
        db.close();
});
'''

Model helper:

'''js
...
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.showRecordId"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>showRecordId (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.showRecordId)
- description and source-code
```javascript
showRecordId = function (value) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.showDiskLoc = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.skip"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>skip (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.skip)
- description and source-code
```javascript
skip = function (value) {
  if(this.s.options.tailable) throw MongoError.create({message: "Tailable cursor doesn't support skip", driver:true});
  if(this.s.state == Cursor.OPEN || this.s.state == Cursor.CLOSED || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  if(typeof value != 'number') throw MongoError.create({message: "skip requires an integer", driver:true});
  this.s.cmd.skip = value;
  this.setCursorSkip(value);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.snapshot"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>snapshot (value)](#apidoc.element.mongoskin.connect.Cursor.prototype.snapshot)
- description and source-code
```javascript
snapshot = function (value) {
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  this.s.cmd.snapshot = value;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.sort"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>sort (keyOrList, direction)](#apidoc.element.mongoskin.connect.Cursor.prototype.sort)
- description and source-code
```javascript
sort = function (keyOrList, direction) {
  if(this.s.options.tailable) throw MongoError.create({message: "Tailable cursor doesn't support sorting", driver:true});
  if(this.s.state == Cursor.CLOSED || this.s.state == Cursor.OPEN || this.isDead()) throw MongoError.create({message: "Cursor is
 closed", driver:true});
  var order = keyOrList;

  // We have an array of arrays, we need to preserve the order of the sort
  // so we will us a Map
  if(Array.isArray(order) && Array.isArray(order[0])) {
    order = new Map(order.map(function(x) {
      var value = [x[0], null];
      if(x[1] == 'asc') {
        value[1] = 1;
      } else if(x[1] == 'desc') {
        value[1] = -1;
      } else if(x[1] == 1 || x[1] == -1) {
        value[1] = x[1];
      } else {
        throw new MongoError("Illegal sort clause, must be of the form [['field1', '(ascending|descending)'], ['field2', '(ascending
|descending)']]");
      }

      return value;
    }));
  }

  if(direction != null) {
    order = [[keyOrList, direction]];
  }

  this.s.cmd.sort = order;
  this.sortValue = order;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.stream"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>stream (options)](#apidoc.element.mongoskin.connect.Cursor.prototype.stream)
- description and source-code
```javascript
stream = function (options) {
  this.s.streamOptions = options || {};
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Cursor.prototype.toArray"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Cursor.prototype.</span>toArray (callback)](#apidoc.element.mongoskin.connect.Cursor.prototype.toArray)
- description and source-code
```javascript
toArray = function (callback) {
  var self = this;
  if(self.s.options.tailable) throw MongoError.create({message: 'Tailable cursor cannot be converted to array', driver:true});

  // Execute using callback
  if(typeof callback == 'function') return toArray(self, callback);

  // Return a Promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    toArray(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
...

Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
...
```



# <a name="apidoc.module.mongoskin.connect.Db"></a>[module mongoskin.connect.Db](#apidoc.module.mongoskin.connect.Db)

#### <a name="apidoc.element.mongoskin.connect.Db.Db"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>Db (databaseName, topology, options)](#apidoc.element.mongoskin.connect.Db.Db)
- description and source-code
```javascript
Db = function (databaseName, topology, options) {
  options = options || {};
  if(!(this instanceof Db)) return new Db(databaseName, topology, options);
  EventEmitter.call(this);
  var self = this;

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Filter the options
  options = filterOptions(options, legalOptionNames);

  // Ensure we put the promiseLib in the options
  options.promiseLibrary = promiseLibrary;

  // var self = this;  // Internal state of the db object
  this.s = {
    // Database name
      databaseName: databaseName
    // DbCache
    , dbCache: {}
    // Children db's
    , children: []
    // Topology
    , topology: topology
    // Options
    , options: options
    // Logger instance
    , logger: Logger('Db', options)
    // Get the bson parser
    , bson: topology ? topology.bson : null
    // Authsource if any
    , authSource: options.authSource
    // Unpack read preference
    , readPreference: options.readPreference
    // Set buffermaxEntries
    , bufferMaxEntries: typeof options.bufferMaxEntries == 'number' ? options.bufferMaxEntries : -1
    // Parent db (if chained)
    , parentDb: options.parentDb || null
    // Set up the primary key factory or fallback to ObjectID
    , pkFactory: options.pkFactory || ObjectID
    // Get native parser
    , nativeParser: options.nativeParser || options.native_parser
    // Promise library
    , promiseLibrary: promiseLibrary
    // No listener
    , noListener: typeof options.noListener == 'boolean' ? options.noListener : false
    // ReadConcern
    , readConcern: options.readConcern
  }

  // Ensure we have a valid db name
  validateDatabaseName(self.s.databaseName);

  // Add a read Only property
  getSingleProperty(this, 'serverConfig', self.s.topology);
  getSingleProperty(this, 'bufferMaxEntries', self.s.bufferMaxEntries);
  getSingleProperty(this, 'databaseName', self.s.databaseName);

  // This is a child db, do not register any listeners
  if(options.parentDb) return;
  if(this.s.noListener) return;

  // Add listeners
  topology.on('error', createListener(self, 'error', self));
  topology.on('timeout', createListener(self, 'timeout', self));
  topology.on('close', createListener(self, 'close', self));
  topology.on('parseError', createListener(self, 'parseError', self));
  topology.once('open', createListener(self, 'open', self));
  topology.once('fullsetup', createListener(self, 'fullsetup', self));
  topology.once('all', createListener(self, 'all', self));
  topology.on('reconnect', createListener(self, 'reconnect', self));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.super_"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.</span>super_ ()](#apidoc.element.mongoskin.connect.Db.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.connect.Db.prototype"></a>[module mongoskin.connect.Db.prototype](#apidoc.module.mongoskin.connect.Db.prototype)

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.addChild"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>addChild (db)](#apidoc.element.mongoskin.connect.Db.prototype.addChild)
- description and source-code
```javascript
addChild = function (db) {
  if(this.s.parentDb) return this.s.parentDb.addChild(db);
  this.s.children.push(db);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.addUser"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>addUser (username, password, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.addUser)
- description and source-code
```javascript
addUser = function (username, password, options, callback) {
  // Unpack the parameters
  var self = this;
  var args = Array.prototype.slice.call(arguments, 2);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  options = args.length ? args.shift() || {} : {};

  // If we have a callback fallback
  if(typeof callback == 'function') return addUser(self, username, password, options, callback);

  // Return a promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    addUser(self, username, password, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.admin"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>admin ()](#apidoc.element.mongoskin.connect.Db.prototype.admin)
- description and source-code
```javascript
admin = function () {
  return new Admin(this, this.s.topology, this.s.promiseLibrary);
}
```
- example usage
```shell
...
'''js
db.bind('article')
db.article.find().toArray(function(err, items) {
  assert.ok(err == null);
});
'''

### db.admin(...)
alias 'new Admin(db, ...)'
### db.grid(...)
alias 'new Grid(db, ...)'
### db.gridStore(...)
alias 'new GridStore(db, ...)'
### collection.bind(extendObject)
each method of extendObject will be bind to collection.
...
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.authenticate"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>authenticate (username, password, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.authenticate)
- description and source-code
```javascript
authenticate = function (username, password, options, callback) {
  if(typeof options == 'function') callback = options, options = {};
  var self = this;
  // Shallow copy the options
  options = shallowClone(options);

  // Set default mechanism
  if(!options.authMechanism) {
    options.authMechanism = 'DEFAULT';
  } else if(options.authMechanism != 'GSSAPI'
    && options.authMechanism != 'DEFAULT'
    && options.authMechanism != 'MONGODB-CR'
    && options.authMechanism != 'MONGODB-X509'
    && options.authMechanism != 'SCRAM-SHA-1'
    && options.authMechanism != 'PLAIN') {
      return handleCallback(callback, MongoError.create({message: "only DEFAULT, GSSAPI, PLAIN, MONGODB-X509, SCRAM-SHA-1 or MONGODB
-CR is supported by authMechanism", driver:true}));
  }

  // If we have a callback fallback
  if(typeof callback == 'function') return authenticate(self, username, password, options, function(err, r) {
    // Support failed auth method
    if(err && err.message && err.message.indexOf('saslStart') != -1) err.code = 59;
    // Reject error
    if(err) return callback(err, r);
    callback(null, r);
  });

  // Return a promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    authenticate(self, username, password, options, function(err, r) {
      // Support failed auth method
      if(err && err.message && err.message.indexOf('saslStart') != -1) err.code = 59;
      // Reject error
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>close (force, callback)](#apidoc.element.mongoskin.connect.Db.prototype.close)
- description and source-code
```javascript
close = function (force, callback) {
  if(typeof force == 'function') callback = force, force = false;
  this.s.topology.close(force);
  var self = this;

  // Fire close event if any listeners
  if(this.listeners('close').length > 0) {
    this.emit('close');

    // If it's the top level db emit close on all children
    if(this.parentDb == null) {
      // Fire close on all children
      for(var i = 0; i < this.s.children.length; i++) {
        this.s.children[i].emit('close');
      }
    }

    // Remove listeners after emit
    self.removeAllListeners('close');
  }

  // Close parent db if set
  if(this.s.parentDb) this.s.parentDb.close();
  // Callback after next event loop tick
  if(typeof callback == 'function') return process.nextTick(function() {
    handleCallback(callback, null);
  })

  // Return dummy promise
  return new this.s.promiseLibrary(function(resolve) {
    resolve();
  });
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.collection"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>collection (name, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.collection)
- description and source-code
```javascript
collection = function (name, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};
  options = shallowClone(options);
  // Set the promise library
  options.promiseLibrary = this.s.promiseLibrary;

  // If we have not set a collection level readConcern set the db level one
  options.readConcern = options.readConcern || this.s.readConcern;

  // Do we have ignoreUndefined set
  if(this.s.options.ignoreUndefined) {
    options.ignoreUndefined = this.s.options.ignoreUndefined;
  }

  // Execute
  if(options == null || !options.strict) {
    try {
      var collection = new Collection(this, this.s.topology, this.s.databaseName, name, this.s.pkFactory, options);
      if(callback) callback(null, collection);
      return collection;
    } catch(err) {
      if(callback) return callback(err);
      throw err;
    }
  }

  // Strict mode
  if(typeof callback != 'function') {
    throw toError(f("A callback is required in strict mode. While getting collection %s.", name));
  }

  // Did the user destroy the topology
  if(self.serverConfig && self.serverConfig.isDestroyed()) {
    return callback(new MongoError('topology was destroyed'));
  }

  // Strict mode
  this.listCollections({name:name}).toArray(function(err, collections) {
    if(err != null) return handleCallback(callback, err, null);
    if(collections.length == 0) return handleCallback(callback, toError(f("Collection %s does not exist. Currently in strict mode
.", name)), null);

    try {
      return handleCallback(callback, null, new Collection(self, self.s.topology, self.s.databaseName, name, self.s.pkFactory, options
));
    } catch(err) {
      return handleCallback(callback, err, null);
    }
  });
}
```
- example usage
```shell
...
        new Server('localhost', 30000),
        new Server('localhost', 30001),
        new Server('localhost', 30002),
]);

var db = new Db('integration_test_', replSet, {w:0, native_parser: (process.env['TEST_NATIVE'] != null)});
// no need open and on('fullsetup', ...)
db.collection('myconnection').find().setReadPreference(ReadPreference.SECONDARY).toArray(function(err, items) {
        db.close();
});
'''

Model helper:

'''js
...
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.collections"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>collections (callback)](#apidoc.element.mongoskin.connect.Db.prototype.collections)
- description and source-code
```javascript
collections = function (callback) {
  var self = this;

  // Return the callback
  if(typeof callback == 'function') return collections(self, callback);
  // Return the promise
  return new self.s.promiseLibrary(function(resolve, reject) {
    collections(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.command"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>command (command, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.command)
- description and source-code
```javascript
command = function (command, options, callback) {
  var self = this;
  // Change the callback
  if(typeof options == 'function') callback = options, options = {};
  // Clone the options
  options = shallowClone(options);

  // Do we have a callback
  if(typeof callback == 'function') return executeCommand(self, command, options, callback);
  // Return a promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    executeCommand(self, command, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.createCollection"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>createCollection (name, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.createCollection)
- description and source-code
```javascript
createCollection = function (name, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 0);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  name = args.length ? args.shift() : null;
  options = args.length ? args.shift() || {} : {};

  // Do we have a promisesLibrary
  options.promiseLibrary = options.promiseLibrary || this.s.promiseLibrary;

  // Check if the callback is in fact a string
  if(typeof callback == 'string') name = callback;

  // Execute the fallback callback
  if(typeof callback == 'function') return createCollection(self, name, options, callback);
  return new this.s.promiseLibrary(function(resolve, reject) {
    createCollection(self, name, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.createIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>createIndex (name, fieldOrSpec, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.createIndex)
- description and source-code
```javascript
createIndex = function (name, fieldOrSpec, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 2);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  options = args.length ? args.shift() || {} : {};
  options = typeof callback === 'function' ? options : callback;
  options = options == null ? {} : options;
  // Shallow clone the options
  options = shallowClone(options);

  // If we have a callback fallback
  if(typeof callback == 'function') return createIndex(self, name, fieldOrSpec, options, callback);
  // Return a promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    createIndex(self, name, fieldOrSpec, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.db"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>db (dbName, options)](#apidoc.element.mongoskin.connect.Db.prototype.db)
- description and source-code
```javascript
db = function (dbName, options) {
  options = options || {};

  // Copy the options and add out internal override of the not shared flag
  var finalOptions = assign({}, this.options, options);

  // Do we have the db in the cache already
  if(this.s.dbCache[dbName] && finalOptions.returnNonCachedInstance !== true) {
    return this.s.dbCache[dbName];
  }

  // Add current db as parentDb
  if(finalOptions.noListener == null || finalOptions.noListener == false) {
    finalOptions.parentDb = this;
  }

  // Add promiseLibrary
  finalOptions.promiseLibrary = this.s.promiseLibrary;

  // Return the db object
  var db = new Db(dbName, this.s.topology, finalOptions)

  // Add as child
  if(finalOptions.noListener == null || finalOptions.noListener == false) {
    this.addChild(db);
  }

  // Add the db to the cache
  this.s.dbCache[dbName] = db;
  // Return the database
  return db;
}
```
- example usage
```shell
...
Usage
========

Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet
...
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.dropCollection"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>dropCollection (name, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.dropCollection)
- description and source-code
```javascript
dropCollection = function (name, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Command to execute
  var cmd = {'drop':name}

  // Decorate with write concern
  decorateWithWriteConcern(cmd, self, options);

  // options
  options = assign({}, this.s.options, {readPreference: ReadPreference.PRIMARY});

  // Check if the callback is in fact a string
  if(typeof callback == 'function') return this.command(cmd, options, function(err, result) {
    // Did the user destroy the topology
    if(self.serverConfig && self.serverConfig.isDestroyed()) return callback(new MongoError('topology was destroyed'));
    if(err) return handleCallback(callback, err);
    if(result.ok) return handleCallback(callback, null, true);
    handleCallback(callback, null, false);
  });

  // Clone the options
  options = shallowClone(self.s.options);
  // Set readPreference PRIMARY
  options.readPreference = ReadPreference.PRIMARY;

  // Execute the command
  return new this.s.promiseLibrary(function(resolve, reject) {
    // Execute command
    self.command(cmd, options, function(err, result) {
      // Did the user destroy the topology
      if(self.serverConfig && self.serverConfig.isDestroyed()) return reject(new MongoError('topology was destroyed'));
      if(err) return reject(err);
      if(result.ok) return resolve(true);
      resolve(false);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.dropDatabase"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>dropDatabase (options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.dropDatabase)
- description and source-code
```javascript
dropDatabase = function (options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};
  // Drop database command
  var cmd = {'dropDatabase':1};

  // Decorate with write concern
  decorateWithWriteConcern(cmd, self, options);

  // Ensure primary only
  options = assign({}, this.s.options, {readPreference: ReadPreference.PRIMARY});

  // Check if the callback is in fact a string
  if(typeof callback == 'function') return this.command(cmd, options, function(err, result) {
    // Did the user destroy the topology
    if(self.serverConfig && self.serverConfig.isDestroyed()) return callback(new MongoError('topology was destroyed'));
    if(callback == null) return;
    if(err) return handleCallback(callback, err, null);
    handleCallback(callback, null, result.ok ? true : false);
  });

  // Execute the command
  return new this.s.promiseLibrary(function(resolve, reject) {
    // Execute command
    self.command(cmd, options, function(err, result) {
      // Did the user destroy the topology
      if(self.serverConfig && self.serverConfig.isDestroyed()) return reject(new MongoError('topology was destroyed'));
      if(err) return reject(err);
      if(result.ok) return resolve(true);
      resolve(false);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.ensureIndex"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>ensureIndex (name, fieldOrSpec, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.ensureIndex)
- description and source-code
```javascript
ensureIndex = function (name, fieldOrSpec, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // If we have a callback fallback
  if(typeof callback == 'function') return ensureIndex(self, name, fieldOrSpec, options, callback);

  // Return a promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    ensureIndex(self, name, fieldOrSpec, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.eval"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>eval (code, parameters, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.eval)
- description and source-code
```javascript
eval = function (code, parameters, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  parameters = args.length ? args.shift() : parameters;
  options = args.length ? args.shift() || {} : {};

  // Check if the callback is in fact a string
  if(typeof callback == 'function') return evaluate(self, code, parameters, options, callback);
  // Execute the command
  return new this.s.promiseLibrary(function(resolve, reject) {
    evaluate(self, code, parameters, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.executeDbAdminCommand"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>executeDbAdminCommand (selector, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.executeDbAdminCommand)
- description and source-code
```javascript
executeDbAdminCommand = function (selector, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Return the callback
  if(typeof callback == 'function') {
    // Convert read preference
    if(options.readPreference) {
      options.readPreference = convertReadPreference(options.readPreference)
    }

    return self.s.topology.command('admin.$cmd', selector, options, function(err, result) {
      // Did the user destroy the topology
      if(self.serverConfig && self.serverConfig.isDestroyed()) return callback(new MongoError('topology was destroyed'));
      if(err) return handleCallback(callback, err);
      handleCallback(callback, null, result.result);
    });
  }

  // Return promise
  return new self.s.promiseLibrary(function(resolve, reject) {
    self.s.topology.command('admin.$cmd', selector, options, function(err, result) {
      // Did the user destroy the topology
      if(self.serverConfig && self.serverConfig.isDestroyed()) return reject(new MongoError('topology was destroyed'));
      if(err) return reject(err);
      resolve(result.result);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.indexInformation"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>indexInformation (name, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.indexInformation)
- description and source-code
```javascript
indexInformation = function (name, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // If we have a callback fallback
  if(typeof callback == 'function') return indexInformation(self, name, options, callback);

  // Return a promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    indexInformation(self, name, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.listCollections"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>listCollections (filter, options)](#apidoc.element.mongoskin.connect.Db.prototype.listCollections)
- description and source-code
```javascript
listCollections = function (filter, options) {
  filter = filter || {};
  options = options || {};

  // Shallow clone the object
  options = shallowClone(options);
  // Set the promise library
  options.promiseLibrary = this.s.promiseLibrary;

  // Ensure valid readPreference
  if(options.readPreference) {
    options.readPreference = convertReadPreference(options.readPreference);
  }

  // We have a list collections command
  if(this.serverConfig.capabilities().hasListCollectionsCommand) {
    // Cursor options
    var cursor = options.batchSize ? {batchSize: options.batchSize} : {}
    // Build the command
    var command = { listCollections : true, filter: filter, cursor: cursor };
    // Set the AggregationCursor constructor
    options.cursorFactory = CommandCursor;
    // Create the cursor
    cursor = this.s.topology.cursor(f('%s.$cmd', this.s.databaseName), command, options);
    // Do we have a readPreference, apply it
    if(options.readPreference) {
      cursor.setReadPreference(options.readPreference);
    }
    // Return the cursor
    return cursor;
  }

  // We cannot use the listCollectionsCommand
  if(!this.serverConfig.capabilities().hasListCollectionsCommand) {
    // If we have legacy mode and have not provided a full db name filter it
    if(typeof filter.name == 'string' && !(new RegExp('^' + this.databaseName + '\\.').test(filter.name))) {
      filter = shallowClone(filter);
      filter.name = f('%s.%s', this.s.databaseName, filter.name);
    }
  }

  // No filter, filter by current database
  if(filter == null) {
    filter.name = f('/%s/', this.s.databaseName);
  }

  // Rewrite the filter to use $and to filter out indexes
  if(filter.name) {
    filter = {$and: [{name: filter.name}, {name:/^((?!\$).)*$/}]};
  } else {
    filter = {name:/^((?!\$).)*$/};
  }

  // Return options
  var _options = {transforms: listCollectionsTranforms(this.s.databaseName)}
  // Get the cursor
  cursor = this.collection(Db.SYSTEM_NAMESPACE_COLLECTION).find(filter, _options);
  // Do we have a readPreference, apply it
  if(options.readPreference) cursor.setReadPreference(options.readPreference);
  // Set the passed in batch size if one was provided
  if(options.batchSize) cursor = cursor.batchSize(options.batchSize);
  // We have a fallback mode using legacy systems collections
  return cursor;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.logout"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>logout (options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.logout)
- description and source-code
```javascript
logout = function (options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};

  // Establish the correct database name
  var dbName = this.s.authSource ? this.s.authSource : this.s.databaseName;
  dbName = options.dbName ? options.dbName : dbName;

  // If we have a callback
  if(typeof callback == 'function') {
    return self.s.topology.logout(dbName, function(err) {
      if(err) return callback(err);
      callback(null, true);
    });
  }

  // Return a promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.s.topology.logout(dbName, function(err) {
      if(err) return reject(err);
      resolve(true);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.open"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>open (callback)](#apidoc.element.mongoskin.connect.Db.prototype.open)
- description and source-code
```javascript
open = function (callback) {
  var self = this;
  // We provided a callback leg
  if(typeof callback == 'function') return open(self, callback);
  // Return promise
  return new self.s.promiseLibrary(function(resolve, reject) {
    open(self, function(err, db) {
      if(err) return reject(err);
      resolve(db);
    })
  });
}
```
- example usage
```shell
...

alias origin 'db.collection(..., function(err, collection) {....})'

origin:

'''js
var db = new Db(...);
db.open(function(err, db) {
    db.collection('myCollection', {strict: true}, function(err, myCollection) {
        // myCollection.find() ...
    });
});
'''

mongoskin:
...
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.removeUser"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>removeUser (username, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.removeUser)
- description and source-code
```javascript
removeUser = function (username, options, callback) {
  // Unpack the parameters
  var self = this;
  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  options = args.length ? args.shift() || {} : {};

  // If we have a callback fallback
  if(typeof callback == 'function') return removeUser(self, username, options, callback);

  // Return a promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    removeUser(self, username, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.renameCollection"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>renameCollection (fromCollection, toCollection, options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.renameCollection)
- description and source-code
```javascript
renameCollection = function (fromCollection, toCollection, options, callback) {
  var self = this;
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};
  // Add return new collection
  options.new_collection = true;

  // Check if the callback is in fact a string
  if(typeof callback == 'function') {
    return this.collection(fromCollection).rename(toCollection, options, callback);
  }

  // Return a promise
  return new this.s.promiseLibrary(function(resolve, reject) {
    self.collection(fromCollection).rename(toCollection, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.stats"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>stats (options, callback)](#apidoc.element.mongoskin.connect.Db.prototype.stats)
- description and source-code
```javascript
stats = function (options, callback) {
  if(typeof options == 'function') callback = options, options = {};
  options = options || {};
  // Build command object
  var commandObject = { dbStats:true };
  // Check if we have the scale value
  if(options['scale'] != null) commandObject['scale'] = options['scale'];

  // If we have a readPreference set
  if(options.readPreference == null && this.s.readPreference) {
    options.readPreference = this.s.readPreference;
  }

  // Execute the command
  return this.command(commandObject, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.Db.prototype.unref"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.Db.prototype.</span>unref ()](#apidoc.element.mongoskin.connect.Db.prototype.unref)
- description and source-code
```javascript
unref = function () {
  this.s.topology.unref();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.connect.GridStore"></a>[module mongoskin.connect.GridStore](#apidoc.module.mongoskin.connect.GridStore)

#### <a name="apidoc.element.mongoskin.connect.GridStore.GridStore"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>GridStore (db, id, filename, mode, options)](#apidoc.element.mongoskin.connect.GridStore.GridStore)
- description and source-code
```javascript
function GridStore(db, id, filename, mode, options) {
  if(!(this instanceof GridStore)) return new GridStore(db, id, filename, mode, options);
  this.db = db;

  // Handle options
  if(typeof options === 'undefined') options = {};
  // Handle mode
  if(typeof mode === 'undefined') {
    mode = filename;
    filename = undefined;
  } else if(typeof mode == 'object') {
    options = mode;
    mode = filename;
    filename = undefined;
  }

  if(id && id._bsontype == 'ObjectID') {
    this.referenceBy = REFERENCE_BY_ID;
    this.fileId = id;
    this.filename = filename;
  } else if(typeof filename == 'undefined') {
    this.referenceBy = REFERENCE_BY_FILENAME;
    this.filename = id;
    if (mode.indexOf('w') != null) {
      this.fileId = new ObjectID();
    }
  } else {
    this.referenceBy = REFERENCE_BY_ID;
    this.fileId = id;
    this.filename = filename;
  }

  // Set up the rest
  this.mode = mode == null ? "r" : mode;
  this.options = options || {};

  // Opened
  this.isOpen = false;

  // Set the root if overridden
  this.root = this.options['root'] == null ? GridStore.DEFAULT_ROOT_COLLECTION : this.options['root'];
  this.position = 0;
  this.readPreference = this.options.readPreference || db.options.readPreference || ReadPreference.PRIMARY;
  this.writeConcern = _getWriteConcern(db, this.options);
  // Set default chunk size
  this.internalChunkSize = this.options['chunkSize'] == null ? Chunk.DEFAULT_CHUNK_SIZE : this.options['chunkSize'];

  // Get the promiseLibrary
  var promiseLibrary = this.options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Set the promiseLibrary
  this.promiseLibrary = promiseLibrary;

  Object.defineProperty(this, "chunkSize", { enumerable: true
   , get: function () {
       return this.internalChunkSize;
     }
   , set: function(value) {
       if(!(this.mode[0] == "w" && this.position == 0 && this.uploadDate == null)) {
         this.internalChunkSize = this.internalChunkSize;
       } else {
         this.internalChunkSize = value;
       }
     }
  });

  Object.defineProperty(this, "md5", { enumerable: true
   , get: function () {
       return this.internalMd5;
     }
  });

  Object.defineProperty(this, "chunkNumber", { enumerable: true
   , get: function () {
       return this.currentChunk && this.currentChunk.chunkNumber ? this.currentChunk.chunkNumber : null;
     }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.exist"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>exist (db, fileIdObject, rootCollection, options, callback)](#apidoc.element.mongoskin.connect.GridStore.exist)
- description and source-code
```javascript
exist = function (db, fileIdObject, rootCollection, options, callback) {
  var args = Array.prototype.slice.call(arguments, 2);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  rootCollection = args.length ? args.shift() : null;
  options = args.length ? args.shift() : {};
  options = options || {};

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // We provided a callback leg
  if(typeof callback == 'function') return exists(db, fileIdObject, rootCollection, options, callback);
  // Return promise
  return new promiseLibrary(function(resolve, reject) {
    exists(db, fileIdObject, rootCollection, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.list"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>list (db, rootCollection, options, callback)](#apidoc.element.mongoskin.connect.GridStore.list)
- description and source-code
```javascript
list = function (db, rootCollection, options, callback) {
  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  rootCollection = args.length ? args.shift() : null;
  options = args.length ? args.shift() : {};
  options = options || {};

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // We provided a callback leg
  if(typeof callback == 'function') return list(db, rootCollection, options, callback);
  // Return promise
  return new promiseLibrary(function(resolve, reject) {
    list(db, rootCollection, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.read"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>read (db, name, length, offset, options, callback)](#apidoc.element.mongoskin.connect.GridStore.read)
- description and source-code
```javascript
read = function (db, name, length, offset, options, callback) {
  var args = Array.prototype.slice.call(arguments, 2);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  length = args.length ? args.shift() : null;
  offset = args.length ? args.shift() : null;
  options = args.length ? args.shift() : null;
  options = options || {};

  // Get the promiseLibrary
  var promiseLibrary = options ? options.promiseLibrary : null;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // We provided a callback leg
  if(typeof callback == 'function') return readStatic(db, name, length, offset, options, callback);
  // Return promise
  return new promiseLibrary(function(resolve, reject) {
    readStatic(db, name, length, offset, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.readlines"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>readlines (db, name, separator, options, callback)](#apidoc.element.mongoskin.connect.GridStore.readlines)
- description and source-code
```javascript
readlines = function (db, name, separator, options, callback) {
  var args = Array.prototype.slice.call(arguments, 2);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  separator = args.length ? args.shift() : null;
  options = args.length ? args.shift() : null;
  options = options || {};

  // Get the promiseLibrary
  var promiseLibrary = options ? options.promiseLibrary : null;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // We provided a callback leg
  if(typeof callback == 'function') return readlinesStatic(db, name, separator, options, callback);
  // Return promise
  return new promiseLibrary(function(resolve, reject) {
    readlinesStatic(db, name, separator, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.unlink"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.</span>unlink (db, names, options, callback)](#apidoc.element.mongoskin.connect.GridStore.unlink)
- description and source-code
```javascript
unlink = function (db, names, options, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 2);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  options = args.length ? args.shift() : {};
  options = options || {};

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // We provided a callback leg
  if(typeof callback == 'function') return unlinkStatic(self, db, names, options, callback);

  // Return promise
  return new promiseLibrary(function(resolve, reject) {
    unlinkStatic(self, db, names, options, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.connect.GridStore.prototype"></a>[module mongoskin.connect.GridStore.prototype](#apidoc.module.mongoskin.connect.GridStore.prototype)

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.chunkCollection"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>chunkCollection (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.chunkCollection)
- description and source-code
```javascript
chunkCollection = function (callback) {
  if(typeof callback == 'function')
    return this.db.collection((this.root + ".chunks"), callback);
  return this.db.collection((this.root + ".chunks"));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.close"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>close (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.close)
- description and source-code
```javascript
close = function (callback) {
  var self = this;
  // We provided a callback leg
  if(typeof callback == 'function') return close(self, callback);
  // Return promise
  return new self.promiseLibrary(function(resolve, reject) {
    close(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
...
Use dburl

'''js
var mongo = require('mongoskin');
var db = mongo.db("mongodb://localhost:27017/integration_tests", {native_parser:true});
db.bind('article');
db.article.find().toArray(function(err, items) {
        db.close();
});
'''

Use ReplSet

'''js
var mongo = require('mongoskin');
...
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.collection"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>collection (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.collection)
- description and source-code
```javascript
collection = function (callback) {
  if(typeof callback == 'function')
    this.db.collection(this.root + ".files", callback);
  return this.db.collection(this.root + ".files");
}
```
- example usage
```shell
...
        new Server('localhost', 30000),
        new Server('localhost', 30001),
        new Server('localhost', 30002),
]);

var db = new Db('integration_test_', replSet, {w:0, native_parser: (process.env['TEST_NATIVE'] != null)});
// no need open and on('fullsetup', ...)
db.collection('myconnection').find().setReadPreference(ReadPreference.SECONDARY).toArray(function(err, items) {
        db.close();
});
'''

Model helper:

'''js
...
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.destroy"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>destroy ()](#apidoc.element.mongoskin.connect.GridStore.prototype.destroy)
- description and source-code
```javascript
function destroy() {
  // close and do not emit any more events. queued data is not sent.
  if(!this.writable) return;
  this.readable = false;
  if(this.writable) {
    this.writable = false;
    this._q.length = 0;
    this.emit('close');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.eof"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>eof ()](#apidoc.element.mongoskin.connect.GridStore.prototype.eof)
- description and source-code
```javascript
eof = function () {
  return this.position == this.length ? true : false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.getc"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>getc (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.getc)
- description and source-code
```javascript
getc = function (callback) {
  var self = this;
  // We provided a callback leg
  if(typeof callback == 'function') return eof(self, callback);
  // Return promise
  return new self.promiseLibrary(function(resolve, reject) {
    eof(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.open"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>open (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.open)
- description and source-code
```javascript
open = function (callback) {
  var self = this;
  if( this.mode != "w" && this.mode != "w+" && this.mode != "r"){
    throw MongoError.create({message: "Illegal mode " + this.mode, driver:true});
  }

  // We provided a callback leg
  if(typeof callback == 'function') return open(self, callback);
  // Return promise
  return new self.promiseLibrary(function(resolve, reject) {
    open(self, function(err, store) {
      if(err) return reject(err);
      resolve(store);
    })
  });
}
```
- example usage
```shell
...

alias origin 'db.collection(..., function(err, collection) {....})'

origin:

'''js
var db = new Db(...);
db.open(function(err, db) {
    db.collection('myCollection', {strict: true}, function(err, myCollection) {
        // myCollection.find() ...
    });
});
'''

mongoskin:
...
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.puts"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>puts (string, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.puts)
- description and source-code
```javascript
puts = function (string, callback) {
  var self = this;
  var finalString = string.match(/\n$/) == null ? string + "\n" : string;
  // We provided a callback leg
  if(typeof callback == 'function') return this.write(finalString, callback);
  // Return promise
  return new self.promiseLibrary(function(resolve, reject) {
    self.write(finalString, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.read"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>read (length, buffer, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.read)
- description and source-code
```javascript
read = function (length, buffer, callback) {
  var self = this;

  var args = Array.prototype.slice.call(arguments, 0);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  length = args.length ? args.shift() : null;
  buffer = args.length ? args.shift() : null;
  // We provided a callback leg
  if(typeof callback == 'function') return read(self, length, buffer, callback);
  // Return promise
  return new self.promiseLibrary(function(resolve, reject) {
    read(self, length, buffer, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.readlines"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>readlines (separator, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.readlines)
- description and source-code
```javascript
readlines = function (separator, callback) {
  var self = this;
  var args = Array.prototype.slice.call(arguments, 0);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  separator = args.length ? args.shift() : "\n";
  separator = separator || "\n";

  // We provided a callback leg
  if(typeof callback == 'function') return readlines(self, separator, callback);

  // Return promise
  return new self.promiseLibrary(function(resolve, reject) {
    readlines(self, separator, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.rewind"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>rewind (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.rewind)
- description and source-code
```javascript
rewind = function (callback) {
  var self = this;
  // We provided a callback leg
  if(typeof callback == 'function') return rewind(self, callback);
  // Return promise
  return new self.promiseLibrary(function(resolve, reject) {
    rewind(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.seek"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>seek (position, seekLocation, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.seek)
- description and source-code
```javascript
seek = function (position, seekLocation, callback) {
  var self = this;

  var args = Array.prototype.slice.call(arguments, 1);
  callback = args.pop();
  if(typeof callback != 'function') args.push(callback);
  seekLocation = args.length ? args.shift() : null;

  // We provided a callback leg
  if(typeof callback == 'function') return seek(self, position, seekLocation, callback);
  // Return promise
  return new self.promiseLibrary(function(resolve, reject) {
    seek(self, position, seekLocation, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.stream"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>stream ()](#apidoc.element.mongoskin.connect.GridStore.prototype.stream)
- description and source-code
```javascript
stream = function () {
  return new GridStoreStream(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.tell"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>tell (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.tell)
- description and source-code
```javascript
tell = function (callback) {
  var self = this;
  // We provided a callback leg
  if(typeof callback == 'function') return callback(null, this.position);
  // Return promise
  return new self.promiseLibrary(function(resolve) {
    resolve(self.position);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.unlink"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>unlink (callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.unlink)
- description and source-code
```javascript
unlink = function (callback) {
  var self = this;
  // We provided a callback leg
  if(typeof callback == 'function') return unlink(self, callback);
  // Return promise
  return new self.promiseLibrary(function(resolve, reject) {
    unlink(self, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.write"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>write (data, close, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.write)
- description and source-code
```javascript
function write(data, close, callback) {
  var self = this;
  // We provided a callback leg
  if(typeof callback == 'function') return _writeNormal(this, data, close, callback);
  // Return promise
  return new self.promiseLibrary(function(resolve, reject) {
    _writeNormal(self, data, close, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.GridStore.prototype.writeFile"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.GridStore.prototype.</span>writeFile (file, callback)](#apidoc.element.mongoskin.connect.GridStore.prototype.writeFile)
- description and source-code
```javascript
writeFile = function (file, callback) {
  var self = this;
  // We provided a callback leg
  if(typeof callback == 'function') return writeFile(self, file, callback);
  // Return promise
  return new self.promiseLibrary(function(resolve, reject) {
    writeFile(self, file, function(err, r) {
      if(err) return reject(err);
      resolve(r);
    })
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.connect.MongoClient"></a>[module mongoskin.connect.MongoClient](#apidoc.module.mongoskin.connect.MongoClient)

#### <a name="apidoc.element.mongoskin.connect.MongoClient.MongoClient"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.</span>MongoClient ()](#apidoc.element.mongoskin.connect.MongoClient.MongoClient)
- description and source-code
```javascript
function MongoClient() {
<span class="apidocCodeCommentSpan">  /**
   * The callback format for results
   * @callback MongoClient~connectCallback
   * @param {MongoError} error An error instance representing the error during the execution.
   * @param {Db} db The connected database.
   */
</span>
  /**
   * Connect to MongoDB using a url as documented at
   *
   *  docs.mongodb.org/manual/reference/connection-string/
   *
   * Note that for replicasets the replicaSet query parameter is required in the 2.0 driver
   *
   * @method
   * @param {string} url The connection URI string
   * @param {object} [options] Optional settings.
   * @param {number} [options.poolSize=5] poolSize The maximum size of the individual server pool.
   * @param {boolean} [options.ssl=false] Enable SSL connection.
   * @param {Buffer} [options.sslCA=undefined] SSL Certificate store binary buffer
   * @param {Buffer} [options.sslCRL=undefined] SSL Certificate revocation list binary buffer
   * @param {Buffer} [options.sslCert=undefined] SSL Certificate binary buffer
   * @param {Buffer} [options.sslKey=undefined] SSL Key file binary buffer
   * @param {string} [options.sslPass=undefined] SSL Certificate pass phrase
   * @param {boolean|function} [options.checkServerIdentity=true] Ensure we check server identify during SSL, set to false to disable
 checking. Only works for Node 0.12.x or higher. You can pass in a boolean or your own checkServerIdentity override function.
   * @param {boolean} [options.autoReconnect=true] Enable autoReconnect for single server instances
   * @param {boolean} [options.noDelay=true] TCP Connection no delay
   * @param {boolean} [options.keepAlive=0] The number of milliseconds to wait before initiating keepAlive on the TCP socket.
   * @param {number} [options.connectTimeoutMS=30000] TCP Connection timeout setting
   * @param {number} [options.socketTimeoutMS=30000] TCP Socket timeout setting
   * @param {number} [options.reconnectTries=30] Server attempt to reconnect #times
   * @param {number} [options.reconnectInterval=1000] Server will wait # milliseconds between retries
   * @param {boolean} [options.ha=true] Control if high availability monitoring runs for Replicaset or Mongos proxies.
   * @param {number} [options.haInterval=10000] The High availability period for replicaset inquiry
   * @param {string} [options.replicaSet=undefined] The Replicaset set name
   * @param {number} [options.secondaryAcceptableLatencyMS=15] Cutoff latency point in MS for Replicaset member selection
   * @param {number} [options.acceptableLatencyMS=15] Cutoff latency point in MS for Mongos proxies selection.
   * @param {boolean} [options.connectWithNoPrimary=false] Sets if the driver should connect even if no primary is available
   * @param {string} [options.authSource=undefined] Define the database to authenticate against
   * @param {(number|string)} [options.w=null] The write concern.
   * @param {number} [options.wtimeout=null] The write concern timeout.
   * @param {boolean} [options.j=false] Specify a journal write concern.
   * @param {boolean} [options.forceServerObjectId=false] Force server to assign _id values instead of driver.
   * @param {boolean} [options.serializeFunctions=false] Serialize functions on any object.
   * @param {Boolean} [options.ignoreUndefined=false] Specify if the BSON serializer should ignore undefined fields.
   * @param {boolean} [options.raw=false] Return document results as raw BSON buffers.
   * @param {boolean} [options.promoteLongs=true] Promotes Long values to number if they fit inside the 53 bits resolution.
   * @param {boolean} [options.promoteBuffers=false] Promotes Binary BSON values to native Node Buffers.
   * @param {boolean} [options.promoteValues=true] Promotes BSON values to native types where possible, set to false to only receive
 wrapper types.
   * @param {number} [options.bufferMaxEntries=-1] Sets a cap on how many operations the driver will buffer up before giving up
on getting a working connection, default is -1 which is unlimited.
   * @param {(ReadPreference|string)} [options.readPreference=null] The preferred ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.connect.MongoClient.connect"></a>[function <span class="apidocSignatureSpan">mongoskin.connect.MongoClient.</span>connect (url, options, callback)](#apidoc.element.mongoskin.connect.MongoClient.connect)
- description and source-code
```javascript
connect = function (url, options, callback) {
  var args = Array.prototype.slice.call(arguments, 1);
  callback = typeof args[args.length - 1] == 'function' ? args.pop() : null;
  options = args.length ? args.shift() : null;
  options = options || {};

  // Validate options object
  var err = validOptions(options);

  // Get the promiseLibrary
  var promiseLibrary = options.promiseLibrary;

  // No promise library selected fall back
  if(!promiseLibrary) {
    promiseLibrary = typeof global.Promise == 'function' ?
      global.Promise : require('es6-promise').Promise;
  }

  // Return a promise
  if(typeof callback != 'function') {
    return new promiseLibrary(function(resolve, reject) {
      // Did we have a validation error
      if(err) return reject(err);
      // Attempt to connect
      connect(url, options, function(err, db) {
        if(err) return reject(err);
        resolve(db);
      });
    });
  }

  // Did we have a validation error
  if(err) return callback(err);
  // Fallback to callback based connect
  connect(url, options, callback);
}
```
- example usage
```shell
...
var Db = mongo.Db;
var Server = mongo.Server;
var MongoClient = mongo.MongoClient;
var ReplSetServers = mongo.ReplSetServers;
...
'''

### MongoClient.connect(...)

returns a 'Db' instance

alias origin 'MongoClient.connect(..., function(err, db) { .... })'

origin:
...
```



# <a name="apidoc.module.mongoskin.cursor"></a>[module mongoskin.cursor](#apidoc.module.mongoskin.cursor)

#### <a name="apidoc.element.mongoskin.cursor.SkinCursor"></a>[function <span class="apidocSignatureSpan">mongoskin.cursor.</span>SkinCursor ()](#apidoc.element.mongoskin.cursor.SkinCursor)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.db"></a>[module mongoskin.db](#apidoc.module.mongoskin.db)

#### <a name="apidoc.element.mongoskin.db.SkinDb"></a>[function <span class="apidocSignatureSpan">mongoskin.db.</span>SkinDb ()](#apidoc.element.mongoskin.db.SkinDb)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.grid_store"></a>[module mongoskin.grid_store](#apidoc.module.mongoskin.grid_store)

#### <a name="apidoc.element.mongoskin.grid_store.SkinGridStore"></a>[function <span class="apidocSignatureSpan">mongoskin.grid_store.</span>SkinGridStore ()](#apidoc.element.mongoskin.grid_store.SkinGridStore)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.helper"></a>[module mongoskin.helper](#apidoc.module.mongoskin.helper)

#### <a name="apidoc.element.mongoskin.helper.isObjectID"></a>[function <span class="apidocSignatureSpan">mongoskin.helper.</span>isObjectID (idstr)](#apidoc.element.mongoskin.helper.isObjectID)
- description and source-code
```javascript
isObjectID = function (idstr) {
  return ObjectID.isValid(idstr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mongoskin.helper.toObjectID"></a>[function <span class="apidocSignatureSpan">mongoskin.helper.</span>toObjectID (hex)](#apidoc.element.mongoskin.helper.toObjectID)
- description and source-code
```javascript
toObjectID = function (hex) {
  if (hex instanceof ObjectID) {
    return hex;
  }
  if (!hex || hex.length !== 24) {
    return hex;
  }
  return ObjectID.createFromHexString(hex);
}
```
- example usage
```shell
...
var myCollection = db.collection('myCollection', {strict: true});
'''

## MongoSkin API part

### module.db(...)
alias 'MongoClient.connect(...)'
### module.helper.toObjectID(hexStr)
convert 'String' to 'ObjectID' instance.
### db.bind(name, options)
alias 'db[name] = db.collection(name, options)'

'''js
db.bind('article')
db.article.find().toArray(function(err, items) {
...
```



# <a name="apidoc.module.mongoskin.mongo_client"></a>[module mongoskin.mongo_client](#apidoc.module.mongoskin.mongo_client)

#### <a name="apidoc.element.mongoskin.mongo_client.SkinMongoClient"></a>[function <span class="apidocSignatureSpan">mongoskin.mongo_client.</span>SkinMongoClient ()](#apidoc.element.mongoskin.mongo_client.SkinMongoClient)
- description and source-code
```javascript
function SkinClass() {
  var args = __slice.call(arguments);
  this._construct_args = args;
  if(useNativeConstructor && arguments.length > 0) {
    args.unshift(null);
    var ctor = NativeClass.bind.apply(NativeClass, args);
    this._native = new ctor();
  } else {
    this._native = null;
  }
  this._emitter = new EventEmitter();
  this._emitter.setMaxListeners(50);
  this._state = STATE_CLOSE;
  this._init && this._init();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mongoskin.utils"></a>[module mongoskin.utils](#apidoc.module.mongoskin.utils)

#### <a name="apidoc.element.mongoskin.utils.makeSkinClass"></a>[function <span class="apidocSignatureSpan">mongoskin.utils.</span>makeSkinClass (NativeClass, useNativeConstructor)](#apidoc.element.mongoskin.utils.makeSkinClass)
- description and source-code
```javascript
function makeSkinClass(NativeClass, useNativeConstructor) {

  function onError (err, args, name) {
    var cb = args.pop();
    if (cb && typeof cb === 'function') {
      cb(err);
    } else {
      console.error("Error occured with no callback to handle it while calling " + name,  err);
    }
  };

  var skinClassName = 'Skin' + NativeClass.name;
  function SkinClass() {
    var args = __slice.call(arguments);
    this._construct_args = args;
    if(useNativeConstructor && arguments.length > 0) {
      args.unshift(null);
      var ctor = NativeClass.bind.apply(NativeClass, args);
      this._native = new ctor();
    } else {
      this._native = null;
    }
    this._emitter = new EventEmitter();
    this._emitter.setMaxListeners(50);
    this._state = STATE_CLOSE;
    this._init && this._init();
  }
  SkinClass._class_name = skinClassName;

  function bindSkin(propName) {
    var fn;
    var desc = Object.getOwnPropertyDescriptor(NativeClass.prototype, propName);
    if(!desc) {
      // console.log('no desc', skinClassName, propName, desc);
      try{
        fn = NativeClass.prototype[propName];
      } catch(e) {}
    } else {
      fn = desc.value;
    }
    if(typeof fn == 'function') {
      SkinClass._bindMethod(propName);
    } else if(desc) {
      if (desc.get) {
        SkinClass._bindGetter(propName);
      }
      if (desc.set) {
        SkinClass._bindSetter(propName);
      }
    // } else {
    //   this will never be called, so comment it.
    //   console.log('no desc and no value', skinClassName, propName);
    }
  }

  SkinClass._bindMethod = function(propName) {
    SkinClass.prototype[propName] = function() {
      var args = __slice.apply(arguments);
      if (this._state == STATE_OPEN) {
        this._native[propName].apply(this._native, args);
      } else {
        this.open(function(err, p_native) {
            if (err) {
              onError(err, args, skinClassName + '.' + propName);
            } else {
              p_native[propName].apply(p_native, args);
            }
        });
      }
      return this;
    }
  }

  SkinClass._bindGetter = function(propName) {
      SkinClass.prototype.__defineGetter__(propName, function() {
          return this._native && this._native[propName];// || this['_prop_' + propName];
      });
  }

  SkinClass._bindSetter = function(propName) {
      SkinClass.prototype.__defineSetter__(propName, function(value) {
          // this['_prop_' + propName] = value;
          this.open(function(err, p_native) {
              if(err) return onError(err, args, skinClassName + '.' + propName);
              p_native[propName] = value;
          });
      });
  }

  for(var propName in NativeClass.prototype) {
    if(propName[0] != '_') bindSkin(propName);
  }

  SkinClass.prototype.open = function(callback) {
    switch (this._state) {
      case STATE_OPEN:
        callback(null, this._native);
        break;
      case STATE_OPENNING:
        this._emitter.once('open', callback);
        break;
      default:
        this._emitter.once('open', callback);
        this._state = STATE_OPENNING;
        var self = this;
        this._open(function(err, p_native) {
            if (err) {
              self._state = STATE_CLOSE;
            } else {
              self._state = STATE_OPEN;
              self._native = p_native;
            }
            self._emitter.emit('open', err, p_native);
        });
    }
    return this;
  }

  SkinClass.prototype.close = function (callback) {
    if (this._state === STATE_CLOSE) {
      callback && callback();
    } else if (this._state === STATE_OPEN) {
      this._state = STATE_CLOSE;
      this._close(callback);
    } else if (this._state === STATE_OPENNING) {
      var self = this;
      this._emitter.once('open', function (err, db) {
          self.close(callback);
      });
    }
    this._native = null;
    return this;
  }

  SkinClass.prototype._close = function(callback) {
    if(this._native.close) {
      this._native.close(callback)
    } else if(callback) {
      callback();
    }
  }

  SkinClass.prototyp ...
```
- example usage
```shell
...
var SkinCursor = require('./cursor').SkinCursor;
var helper = require('./helper');
var utils = require('./utils');

/**
* Constructor
*/
var SkinCollection = exports.SkinCollection = utils.makeSkinClass(Collection);

/**
* bind extend functions to collection
*
* e.g.
*
* db.bind('article').bind({
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

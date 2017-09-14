# Sublime Ember Snippets

Ember.js ES6, Ember Data, Mirage & Handlebars snippets for Sublime Text editor

## Installation

* Clone this repo:

    ```bash
    git clone git@github.com:romulomachado/sublime-ember-snippets.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/sublime-ember-snippets
    ```

* Restart ST.

## Usage

* [Ember](/ember)
    * [import Ember from ember](/ember#ime)
    * [const { } = Ember](/ember#ce)
* [Skeletons](/skeletons)
    * [Adapters](/skeletons#adapters)
        * [ActiveModelAdapter](/skeletons#activeadapter)
        * [JSONAPIAdapter](/skeletons#jaadapter)
        * [RESTAdapter](/skeletons#adapter)
    * [boundHelper](/skeletons#boundhelper)
    * [Component](/skeletons#component)
    * [Controller](/skeletons#controller)
    * [Helper](/skeletons#helper)
    * [Initializer](/skeletons#initializer)
    * [Mixin](/skeletons#mixin)
    * [Model](/skeletons#model)
    * [Object](/skeletons#object)
    * [Route](/skeletons#route)
    * [Serializers](/skeletons#serializers)
        * [ActiveModelSerializer](/skeletons#activeserializer)
        * [JSONAPISerializer](/skeletons#jaserializer)
        * [RESTSerializer](/skeletons#serializer)
    * [Service](/skeletons#service)
    * [Utility](/skeletons#utility)
* [Ember.Component](/component)
    * [didDestroyElement](/component#diddestroyelement)
    * [didInsertElement](/component#didinsertelement)
    * [didReceiveAttrs](/component#didreceiveattrs)
    * [didRender](/component#didrender)
    * [didUpdateAttrs](/component#didupdateattrs)
    * [willClearElement](/component#willclearelement)
    * [willDestroyElement](/component#willdestroyelement)
    * [willUpdate](/component#willupdate)
* [EmberData](/data)
    * [attr](/data#attr)
    * [belongsTo](/data#bt)
    * [findAll](/data#fall)
    * [findRecord](/data#frecord)
    * [hasMany](/data#hM)
    * [peekAll](/data#pall)
    * [peekRecord](/data#precord)
    * [query](/data#qall)
    * [queryRecord](/data#qrecord)
* [Ember.Enumberable](/enumerable)
    * [every](/enumerable#every)
    * [filterBy](/enumerable#filterby)
    * [firstObject](/enumerable#first)
    * [isAny](/enumerable#isany)
    * [isEvery](/enumerable#isevery)
    * [lastObject](/enumerable#last)
    * [mapBy](/enumerable#mapby)
    * [some](/enumerable#some)
    * [toArray](/enumerable#toarray)
* [Ember.Object](/object)
    * [actions](/object#actions)
    * [alias](/object#alias)
    * [computed](/object#computed)
    * [get](/object#get)
    * [init](/object#init)
    * [inject](/object#inject)
    * [lget](/object#lget)
    * [observer](/object#observer)
    * [set](/object#set)
    * [super](/object#super)
* [Ember.Route](/route)
    * [afterModel](/route#after)
    * [model](/route#model)
    * [setupController](/route#setupC)
* [test-helpers](/test-helpers)
    * [andThen](/test-helpers#andthen)
    * [click](/test-helpers#click)
    * [fillIn](/test-helpers#fillin)
    * [find](/test-helpers#find)
    * [keyEvent](/test-helpers#keyevent)
    * [pauseTest](/test-helpers#pause)
    * [triggerEvent](/test-helpers#trigger)
    * [visit](/test-helpers#visit)
    * [wait()](/test-helpers#wait)
* [Ember Modules (RFC 176 :fire:)](/modules)
    * @ember/application
        * [Application](/modules#imapp)
        * [ApplicationInstance](/modules#imappinstance)
        * [deprecate](/modules#imdeprecate)
        * [deprecateFunc](/modules#imdeprecatefunc)
        * [getOwner](/modules#imgetowner)
        * [onLoad](/modules#imonload)
        * [Resolver](/modules#imresolver)
        * [runLoadHooks](/modules#imrunloadhooks)
        * [setOwner](/modules#imsetowner)
    * @ember/array
        * [EmberArray](/modules#imarray)
        * [ArrayProxy](/modules#imarrayproxy)
        * [A](/modules#imemberarray)
        * [isArray](/modules#imisarray)
        * [makeArray](/modules#immakearray)
        * [MutableArray](/modules#immutarray)
    * Base
        * [$](/modules#im$)
        * [Enumerable](/modules#imenum)
        * [EmberError](/modules#imerr)
        * [instrument](/modules#iminstrument)
        * [reset](/modules#imreset)
        * [subscribe](/modules#imsubscribe)
        * [unsubscribe](/modules#imunsubscribe)
    * @ember/component
        * [Checkbox](/modules#imcheckbox)
        * [Component](/modules#imcomponent)
        * [helper](/modules#imhelper)
        * [helperHelper](/modules#imhelperhelper)
        * [TextArea](/modules#imtextarea)
        * [TextField](/modules#imtextfield)
    * @ember/controller
        * [Controller](/modules#imcontroller)
        * [inject](/modules#iminjectcontroller)
    * @ember/debug
        * [assert](/modules#imassert)
        * [ContainerDebugAdapter](/modules#imcontainerdebugadapter)
        * [debug](/modules#imdebug)
        * [DataAdapter](/modules#imdebugdataadapter)
        * [inspect](/modules#iminspect)
        * [registerDeprecationHandler](/modules#imregisterdeprecationhandler)
        * [registerWarnHandler](/modules#imregisterwarnhandler)
        * [runInDebug](/modules#imrunindebug)
        * [warn](/modules#imwarn)
    * @ember/engine
        * [Engine](/modules#imengine)
        * [EngineInstance](/modules#imengineinst)
        * [getEngineParent](/modules#imgetengineparent)

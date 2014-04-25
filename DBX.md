# A dbx/mabisz projekt miatt szükséges változások

Ember Model, 1. kiinduló verzió: e6f649465f
Ember Model, 2. kiinduló verzió: 58c511fc46

* A szerver által visszaadott JSON a mérvadó. Rekord mentésénél a visszaadott JSON-ban lévő praméterekkel frissítsük a rekord-ot.
* Az embedded hasMany rekordok megduplázódtak mentésnél. Viszont úgy tűnik, ezt a problémát a 2. kinduló verzióban már javították.
* Embedded hasMany és belongsTo child rekordokat változtatva a partner rekord dirty-vé válik. Csak, teszt, upstream javították.

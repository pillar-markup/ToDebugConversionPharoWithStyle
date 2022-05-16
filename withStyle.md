Programming is a lot more than just writing algorithms or programs. Programming is all about communication. Communication with others: not only with the other programmers who will be involved in your development effort, but also with yourself. Indeed, finding good names is a really important task because using the right name often opens the door to new spaces where your design can bloom and expand. 
sizeJustRead
readSize
sizeJustRead
AbstractSyntaxTreeNode
NewInlineParser
CleanerInlineParser
MicHTMLWriter
MCVersionSaved
RubBoundsChanged
OpeningFile
ContactBook
ContactDictionary
CmdMessage
time_of_day
Transcript 	"global variable"
PackageGlobalOrganizer	"class variables"
classExtensionSelectors
classTags
MaxLimit := 10.
maxLimit := 20.
MaxLimit
>>> 10
MAXLIMIT
MaxLimit
MAXLIMIT
	| methodsNames |
	methodsNames := aClass selectors.
	methodsNames do: [ :each | names add: each ]
	| methodsNames |
	methodsNames := aClass selectors.
	methodsNames do: [ :each | names add: each ]
newSizeOfArray := numberOfAdults size max: numberOfChildren size
anInteger := numberOfAdults size max: numberOfChildren size
selectFrom: aBeginningDate to: anEndDate
selectFrom: aDate to: anotherDate
ifTrue: action1 ifFalse: action2
copyFrom: start to: stop
findFirst: aBlock ifNone: errorBlock 
paddedTo: newLength with: anObject 
phoneNumber 
name
labelForPerson
isAlarmEnabled
	numberOfTires 
	numberOfDoors

"In class AlarmClock..."
	time 
	alarmTime

"In class TypeSetter..."
	page
	font 
	outputDevice
	tireCount
	selectors do: [:each | self pushDown: each].
	selectors do: [:each | class removeMethod: each]
aFace beSurprised
aConfiguration flattenPropertiesInto: aDictionary
	^ [
		(self needsMethodSignatureOnMultipleLinesFor: aMethodNode)
			ifTrue: [ self newLine ]
			ifFalse: [ self space ] ]
	^ (self needsMethodSignatureOnMultipleLinesFor: aMethodNode)
			ifTrue: [ self newLine ]
			ifFalse: [ self space ]
fileSystem atKey: index putFile: pathName
fileSystem definitionAt: aKey put: definition
	^ tiles
	^ tiles
    "Set a root node"
    ^ root := rootNode

    root := rootNode
	^ tiles ifNil: [ tiles := OrderedCollection new ]
	tiles := aCollection 
	^ tiles ifNil: [ tiles := OrderedCollection new.
	^ tiles ifNil: [ tiles := OrderedCollection new. ^tiles ]
	tiles ifNil: [ tiles := OrderedCollection new ].
	^ tiles
	tiles := aCollection 
	tiles := aCollection 
	self basicMethod: aCompiledMethod.
	self signal: MethodChanged
	method := aCompiledMethod
	^ path
	^ self path asString
	^ super annotation
		==>
			[ :array | array second parameters: (array third ifNil: [ SmallDictionary new ]) ]
	^ super annotation
		==>
			[ :array | array second newParameters: (array third ifNil: [ SmallDictionary new ]) ]

	| parameters |
	parameters := self checkKeysOf: aCollection.
	^ self new
		hadAllKeys: aCollection = parameters;
		parameters: parameters;
		yourself
	| parameters |
	parameters := self checkKeysOf: aCollection.
	^ self new
		hadAllKeys: aCollection = parameters;
		parameters: parameters;
		yourself
	"A comment following the guidelines."
	
	| temporary variables |
	statements
	"Add newObject to the end of the receiver. Answer newObject."

	lastIndex = array size ifTrue: [ self makeRoomAtLast ].
	lastIndex := lastIndex + 1.
	array at: lastIndex put: newObject.
	^ newObject
	"Return a collection for wich each element is not included in 'nonEmpty'"
	
	^ collectionWithoutNil 
" return a collection for wich each element is not included in 'nonEmpty' "
	^ collectionWithoutNil 

" return a collection not including equal elements "
	^collectionWithoutEqualElements 
super initialize.
symbols := Bag new.
names := Set new

	super initialize.
	symbols := Bag new.
	names := Set new
	"Takes the last word in uppercase as a symbol and eventually add it to the bag symbols"

	name := aName copy.
	self getUpperCase.
	self stemSymbolFrom: aName.
	self toUpperCase.
	^ symbol
	"Takes the last word in uppercase as a symbol and eventually add it to the bag symbols"
	name := aName copy.
	self getUpperCase.
	self stemSymbolFrom: aName.
	self toUpperCase.
	^ symbol

	| stemmer symbol |
	stemmer := SymbolStemmer new.
	symbol := stemmer performCrawling: aName.
	^ symbol

	|stemmer symbol|
	stemmer:=SymbolStemmer new.
	symbol:=stemmer performCrawling:aName.
	^symbol

	(self canDrawDecoratorsOn: aCanvas) ifFalse: [ ^ self ].
	self drawOnAthensCanvas: aCanvas.
	next drawOnAthensCanvas: aCanvas bounds: aRectangle color: aColor
	(Person new
		name: 'Robin';
		city: 'Ottawa'; 
		country: 'Canada').
	(Person new
	name: 'Robin'; 
	city: 'Ottawa'; 
	country: 'Canada').

	| stemmer symbol |
	stemmer := SymbolStemmer new.
	symbol := stemmer performCrawling: aName.
	^ symbol
	|stemmer symbol|
      stemmer:=SymbolStemmer new. 
  symbol:=stemmer performCrawling: aName.
   ^symbol
	"this method is here to find the paragraph in the chain, instead of relying on implementing #doesNotUnderstand: !!!"

	| p |
	p := next.
	[ p isNotNil and: [ p isKindOf: RubParagraph ] ]
		whileFalse: [ p := p next ].
	^ p
	"this method is here to find the paragraph in the chain, instead of relying on implementing #doesNotUnderstand: !!!"

	| p |
	
	p := next.
	
	[ p  isNotNil and: [ p isKindOf: RubParagraph ] ] whileFalse: [ 
		p := p next.
	].

	^p
	"Returns size of a tree - number of nodes in a tree"
	self root isNil 
		ifTrue: [ ^0 ].
	^ self size: self root
	"Returns size of a tree - number of nodes in a tree"
	self root isNil 
	ifTrue: [ ^0 ].
	^self size: self root.
	"Returns depth of a tree starting from the given node"

	| leftDepth rightDepth |
	leftDepth := -1.
	aNode leftChild isNotNil 
		ifTrue: [ leftDepth := self depth: aNode leftChild ].
	rightDepth := -1.
	aNode rightChild isNotNil 
		ifTrue: [ rightDepth := self depth: aNode rightChild ].	
	leftDepth > rightDepth
		ifTrue: [ ^ 1 + leftDepth ]
		ifFalse: [^ 1 + rightDepth ].
	"Returns depth of a tree starting from the given node"
	| leftDepth rightDepth |
	leftDepth := -1.
	aNode leftChild isNotNil 
	ifTrue: [ leftDepth := self depth: aNode leftChild ].
	rightDepth := -1.
	aNode rightChild isNotNil 
	ifTrue: [ rightDepth := self depth: aNode rightChild ].
	
	( leftDepth > rightDepth )
	ifTrue: [ ^ (1 + leftDepth) ]
	ifFalse: [^ (1 + rightDepth ) ].
block := [ :arg |
  | local | 
  ... local ... ]
block := [: arg | 
  ... local ... ]
    "Return collection printed as 'a, b, c' "
    "#('a' 'b' 'c') asCommaString >>> 'a, b, c'"
    
    ^ String streamContents: [:s | self asStringOn: s delimiter: ', ']
	"Answer number of days (an instance of Integer) from 
	the receiver to January 1, 1901."

	^ day
result := self employees
	collect: [:employee | employee salary > amount].
"Store the employees who have a salary greater than in result." 
result := self employees
	collect: [:employee |  employee salary > amount].
createShell
	"Create the receiver's shell. Hook the focus callback."
createShell
	"The receiver's shell is created. The focus callback is hooked."
	"If the receiver is not nil, pass it as argument to the ifNotNilBlock block
	else execute the nilBlock block "
	
	"(nil ifNil: [42] ifNotNil: [:o | o + 3 ] ) >>> 42"
	"(3 ifNil: [42] ifNotNil: [:o | o + 3 ]) >>> 6"
	
	^ ifNotNilBlock cull: self
	"Split the argument using the receiver as a separator."
	"optimized version for single delimiters"
	"($/ split: '/foo/bar')>>>#('' 'foo' 'bar') asOrderedCollection"
	"([:c| c isSeparator] split: 'aa bb cc dd') >>> #('aa' 'bb' 'cc' 'dd') asOrderedCollection"
		
	| result |
	result := OrderedCollection new: (aSequenceableCollection size / 2) asInteger.
	self split: aSequenceableCollection do: [ :item |
		result add: item ].
	^ result

For the Class part:  
	State a one line summary. For example, "I represent a paragraph of text".

For the Responsibility part: 
	Three sentences about my main responsibilities - what I do, what I know.

For the Collaborators Part: 
	State my main collaborators and one line about how I interact with them. 

Public API and Key Messages
	- message one   
	- message two 
	- (for bonus points) how to create instances.

One simple example is simply gorgeous.
 
Internal Representation and Key Implementation Points.

Implementation Points
that := self doAndReturnThat.
that ifNotNil: [self doSomethingWith: that]
	"Returns depth of a tree starting from the given node"
	...
	^ leftDepth > rightDepth
		ifTrue: [ 1 + leftDepth ]
		ifFalse: [ 1 + rightDepth ]
	"Returns depth of a tree starting from the given node"
	...
	leftDepth > rightDepth
		ifTrue: [ ^ 1 + leftDepth ]
		ifFalse: [ ^ 1 + rightDepth ]
stream ...
^ stream contents
list := OrderedCollection new: 10000.
1 to: 10000 do: [ :i |
	list add: i ]
list := OrderedCollection new: 100000.
1 to: 100000 do: [ :i |
	list add: i ] ] bench 
"for 100,000 get 165.901 per second"
"for 10,000 get 5484.903 per second"

[| list |
list := OrderedCollection new.
1 to: 100000 do: [ :i |
	list add: i ] ] bench 
"for 100,000 get 79.368 per second" 
"for 10,000 get 5278.544 per second"

	self initialize.
	self continue

	super initialize.
	self continue
	super bar.
	self continue
	self bar.
	self continue
	super initialize.
	turn := 0.

	self assert: Game new turn equals: 0
	^ self basicNew 
		initializeTiles: aNumber ; 
		yourself
	tiles := Array new: aNumber

	^ super new initialize

		default := 'no'.
		^ super initialize

		default := 'no'.
		super initialize

		super initialize
		default := 'no'.

	| uUMLClass |
	uUMLClass := UMLClass named: 'ComixSerie'.
	uUMLClass instVar: 'name'.
	self assert: uUMLClass variables includes: 'name'

	| uUMLClass |
	uUMLClass := UMLClass named: 'ComixSerie'.
	uUMLClass instVar: 'name'.
	self assert: (uUMLClass variables includes: 'name')
>>> 9 
>>> 7 
	(row at: 'target') = 'Iris-setosa' 
		ifTrue: [ a add: row asArray ] ].
	( (row at: 'target') = 'Iris-setosa') 
		ifTrue: [ a add: (row asArray) ] ].
	"Returns depth of a tree starting from the given node"
	
	| leftDepth rightDepth |
	leftDepth := -1.
	aNode leftChild isNotNil 
		ifTrue: [ leftDepth := self depth: aNode leftChild ].
	rightDepth := -1.
	aNode rightChild isNotNil 
		ifTrue: [ rightDepth := self depth: aNode rightChild ].
	^ leftDepth > rightDepth
		ifTrue: [ 1 + leftDepth ]
		ifFalse: [ 1 + rightDepth ]
	"Returns depth of a tree starting from the given node"
	| leftDepth rightDepth |
	leftDepth := -1.
	aNode leftChild isNotNil 
	ifTrue: [ leftDepth := self depth: (aNode leftChild) ].
	rightDepth := -1.
	aNode rightChild isNotNil 
	ifTrue: [ rightDepth := self depth: (aNode rightChild) ].
	
	( leftDepth > rightDepth )
	ifTrue: [ ^ (1 + leftDepth) ]
	ifFalse: [^ (1 + rightDepth ) ].
a := 12.  
{a} printString
>>> #(12)
a := 12.  
(a) printString
>>> 12
	ifTrue:[ lastNode := curNode ]
	ifFalse:[ lastNode next: curNode ]
	ifTrue:[ lastNode := curNode ]
	ifFalse:[ lastNode next: curNode ]
	ifTrue:[ lastNode := curNode ]
	ifFalse:[ lastNode next: curNode ]
	ifTrue: [ lastNode := curNode ]
	ifFalse: [ lastNode next: curNode ]
>>> 'Pharo with Style'
>>> '551.890 per second'
  s := ''.
  1 to: 10000 do: [ :i | s := s, i asString ]  ] bench
>>> '8.465 per second'
>>> '6313.137 per second'
  s := ''.
  1 to: 1000 do: [ :i | s := s, i asString ]  ] bench  
>>> '967.819 per second'

	anotherObject bar: super.
	self continue.

	anotherObject bar: self.
	self continue.
	^ super
	^ self
	... code1

action2
	... code2

some method 
	x <y 
		ifTrue: [ self action1 ]
		ifFasel: [ self action2  ]
action2 := [ ... code2 ]

some method 
	x <y 
		ifTrue: [ action1 value ]
		ifFasel: [ action2 value ]
	body of a long block

anObject use: [ self messageWithBlock ]
>>> 'aPerson ('John Doe')'
>>> 'John Doe' 
	"Answer a String whose characters are a description of the receiver. 
	If you want to print without a character limit, use fullPrintString."

	^ self printStringLimitedTo: 50000
	"Answer a String whose characters are a description of the receiver.
	If you want to print without a character limit, use fullPrintString."

	^self printStringLimitedTo: limit using: [:s | self printOn: s]
	"Answer a String whose characters are a description of the receiver
	produced by given printBlock. It ensures the result will be not bigger than given limit"

	| limitedString |
	limitedString := String streamContents: printBlock limitedTo: limit.
	limitedString size < limit ifTrue: [^ limitedString].
	^ limitedString , '...etc...'
	self displayIdentifierOn: aStream.
	aStream 
		nextPutAll: ' (';
		nextPutAll: self tally printString;
		nextPutAll: ')'
	self displayIdentifierOn: aStream.
	aStream 
		nextPutAll: ' (';
		print: self tally;
		nextPutAll: ')'
	"Have anObject print itself on the receiver."

	anObject printOn: self

	^ String streamContents: [ :stream |
		stream
			nextPutAll: '"protocol: '; 
			nextPutAll: protocol printString;
			nextPut: $"; cr; cr;
			nextPutAll: sourceCode ]	

	^ String streamContents: [ :stream |
		stream
			nextPutAll: '"protocol: '; 
			print: protocol;
			nextPut: $"; cr; cr;
			nextPutAll: sourceCode ]	
>>> '#foo'
>>> 'foo'
>>> 'foo'
>>> '''foo'''
    Transcript show: 'foo' ; cr  
   self traceCr: 'foo'
	
    Transcript << 'Closing ' << self class name; cr; endEntry
Closing MicCodeBlock
Closing MicCodeBlock
Closing MicCodeBlock
Closing MicCodeBlock
Closing MicCodeBlock
Closing MicCodeBlock
Closing MicCodeBlock
Closing MicHeaderBlock
Closing MicHeaderBlock
Closing MicHeaderBlock
Closing MicHeaderBlock
Closing MicListItemBlock
Closing MicListItemBlock
Closing MicOrderedListBlock
	instanceVariableNames: 'parent children parser logStream'
	classVariableNames: ''
	package: 'Microdown-Model'
	super initialize. 
	children := OrderedCollection new.
   logStream := WriteStream on: (String new: 1000)
	logStream << 'Closing ' << self class name; cr
	logStream := aStream
	instanceVariableNames: 'parent children parser logStream'
	classVariableNames: 'DefaultStream'
	package: 'Microdown-Model'
	DefaultStream := aStream
	self logStream: (WriteStream on: (String new: 1000))
	self reset
	super initialize. 
	children := OrderedCollection new.
   logStream := DefaultStream
	Error signal: 'Oh no!'
	x isSomethingBad
		ifTrue: [ self error: 'Oh no!' ]
	Error signal: 'Oh no! Really no!'
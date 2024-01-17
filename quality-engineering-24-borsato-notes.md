# Quality engineering - Prof. Bertocco 23-24

Alessandro Borsato Notes of the lectures (some of them are missing)
These notes are meant to be personal, after many requests I decided to make them public, also under the permission of Professor Bertocco.
This is not an offial source of information about the course, these ones are lectures, moodle material and recommended books!

I cleaned up a little bit the notes, but I know there are some unclear phrases, if you notice something not meant to be there contact me please!

**Also if this repository is useful to you, please leave a star!**

Contacts:
alessandro.borsato.1@studenti.unipd.it
alessandroborsato.it

*Since I am an Italian student, some phrases could contain some Italian and English language mixed up (hope this won't be too annoying to readers).
Again, these notes were meant to be personal, I decided to share them after many people asked me to let them public.
I hope these will help you preparing the exam, break a leg!*

# Lecture. 1
## topics and rules
### goals
1. QMS Quality Management System: understand it
2. Quality tools and techiques, get and mantain iso 9001
3. understand total quality

## company profiles

relation between margin of profit of a product and the numbers of it to sell is hyperbolic (maybe price too high leads to the need of hyper production)

also another prospective is to see the requirements of space to produce items faster

1 minute working time more out of 4 h: 0.4% revenue less

When a product starts to have customization, the production line could break
In fact it is easier to configure a straight production line instead of a multiple-choice one (in software this means test all possible configurations, it makes the product development more probably defective)

## we need methods
1. lean production
2. Toyota system
3. statistical process/quality control

To make the company more competitive in the market we can:
- reduce the price of our product. This choice is simple and can be understood by everyone in terms of costs. But we have to consider that a 10% discount costs the job to 8 employees. To make the company profitable we have to fire 8 people to obtain a lower price in the final product. So it starts to be a reasoning in terms of resources and effiency in using them.
- reduce the risk of damages/defects in products. This action is not so well understood, but it has similar damages in the company balance

consideration for students! consider the cost of a software bug, in different environments (crm, bank online, industrial machinery, embedded system, microprocessor)
Solution: Automatic testing and using a tracking system could be an intelligent way to avoid defects

# lecture 2
Book review exercise: how we can build a book reviews company and make it profitable?
How many people we need, how we need to structure activities?
The exercise is free, just to introduce next lectures.

# lecture 3

Depending on how we organize ourselves things can change.

In a company activities need goals. If we don't have them we don't know what to do, what's the direction?

## example
Suppose that we are a company of approx. 20 ppl

People use to specialize, we have an ensemble of professionals.

## ? exercise
Assignment: If our general goal is to provide a book review, what our company would be like?
(work in groups)

### my groups solution

- ceo (1 person)
- reviewers (people divided in genres) 15 or less ppl
    - history
    - science
    - ...
- sales (at least 1 person)
- marketing (also can be the same as sales) 
- accountability (to get everyone paied) (at least 1 person)
- back office (internal activities-lawyer) (1 or 0 people)
- secretary / assistance /customer care (1 person)

### other groups 

- person can be the same or different depends on...

Prof: NO: decision cannot be random

## activities found
- (*) review --> provides summary & evaluation (draft)
- (*) proof read --> provides S & E ready for the customer
- () marketing --> makes the company known
- () accountant --> administation (€)
- () human resources --> take care of workers (salary, vacation, hire, ..)
- (*) commercial --> takes care of review requests, sell, propose, looks for clients
- () CEO --> makes company decisions
- () customer support --> provides support after the review has been provided
- () IT technician --> website, ..
- () inner services: legal aspects, secretariant, IT management, warehouse

(*) = money related
() = useful but not money related

[ ] Wikipedia:  Michael Porter theory https://en.wikipedia.org/wiki/Michael_Porter

I need to care about value chain.

Goals are related to the chain of money.

An activity have sense if we have a goal, at least for the ones we have in the value chain, the ones marked with "(*)".

## 2nd exercise

- (*) review --> provides summary & evaluation (draft)
- (*) proof read --> provides S & E ready for the customer
- (*) commercial --> takes care of review requests, sell, propose, looks for clients
- overheads (IT: tutti gli altri)

[Note: companies could be quite different, the numbers are invented]

### first question: how many are we?
- 20 reviewers
- 2 commercials (many people can rise this number if needed)
- 1 administration
- 1 secretariant
- 1 ceo

Total: 25 people


## professor's solution
*Redemption rate*: how many sells we have w.r.t. numbers of proposal we make?

(higher it is, higher is the efficience of sales)

From ISTAT, the *mean salary* is 30K/yr, so for 20 people we need 750K/yr = balance for our company

*amount of working hours per year*: 1600h/yr

Maybe it's not true for sales and ceo, who usually gets paid more

Pricing: ???

Target price: 100€/review
At this price we need 7500 reviews/yr to stay in businness

sales=187/week (based on istat)

review & proofread = 1600*20/7500 = 4,27 h per review, unsustainable

### exercise : trasform to excel the problem we discussed

# lecture 6
missing, the following notes are from a photo received

## process management
iso 9000

List of activities
- predefined result
- repeated, same way

Process
- set of activities
    - input
    - output
    - providers {inner,external}
    - (process) customers {inner, external}

Title 
Description (1/2 sentences)  IEEE 802...
Parameters
- goals
mandatory regulations/laws {voluntary, inner}
- measurements
- added value


# lecture 7

## recap of previous lectures

Process

Input (providers) ---> [title description] ---> output (process customers)

Parameters:
- goals
- measurements
- resources
- mandatory rules {ext,int}

*Motto: less resources and better goals*

## exercise: Computer shop

What are the main processes we have in such a company?
-title + description

Our group solution:
### figures
- **technician**: assembles computers, intstalls software
- **shop assistant**: helps customers in finding what they need, maybe something more
- **cashier**: sells the product and write the recipes
- **manager**: (if it's a big company)
- **accountant**: takes care of the taxes/financial stuff
- **supplier**: takes care of the stocks in the back, and also
- **post-sale assistant**: assistance post-sale (customer service, insurances, ...)
- **buyier**: buys parts we need 

### Processes
In the following lists elements are in the form "**name**: description"
**selling items**: sell an item to a customer

**assembling/building computers**: select parts to build a computer

**installing software**: installs software on assembled machines

**compile a refund**: compiles a refund policy paper to send to the supplier

**buy products**: buy pc parts

**pay taxes**: pay taxes
End of our group solution.

### Other solutions: merged by professor

**selling items**: We sell an item to a customer either in stock or by ordering parts. Or install & setup service --> delivery

**building computers**: assemble a computer from parts in the warehouse

**buy parts**: from orders and in stock info buy parts from the warehouse

**on site install**: go to customer site and install a computer, 1st run with the customer

**customer support**: after customer request fix a porblem, on site or in the house

**order evaluation**: check feasibility of an order

**testing**: test if the computer is properly working

??? **deciding prices, write technical documents**

## choose your production style
Many process: specialized people

But we can choose our production style:
1. Bench production (ITALIAN: produzione lotti)
Prepare areas where competence are together
cons: need flexible machines

2. Lean production
(take 1 order, build 1 item, sell 1 item)

other production styles are mentioned on slides in moodle!

## Example where is preferable the lean production
In this example the lean approach is preferable.

I may have options with processes, start to have a flow chart in activities.. not at this level, each process takes simply inputs.

Some internal rules examples:
- at the end of every day check the warehouse
- ...


# lecture 8

**Selling items**: We sell an item to a customer either in stock or by ordering parts. Or install & setup service --> delivery

**Building computers**: assemble a computer from parts in the warehouse

**Buy parts**: from orders and in stock info buy parts from the warehouse

**On site install**: go to customer site and install a computer, 1st run with the customer

**Customer support**: after customer request fix a problem, on site or in the house

**Order evaluation**: check feasibility of an order

**(Testing)**: test if the computer is properly working

## Aim of today: design a top view of each process

(Define input, output)

We take as an example the computer shop company.

Reason: understand the inputs could suggest us if something could be automatized

Deployment: we transform general goal in details to perform it. We also create more order.

Things to decide
- how many items to sell
- how many hours use to build computers
- what does it mean to provide customer support?

Quality is defined after defining the activities, because we can find what does 

Suppose also something goes wrong:
- who is doing what
- who is waiting for what
- ...

Need to find connections and flow of the activities.

In some flows we need someone to start the stream (like a client request).

## how we can start detailing the processes
- follow value chain
- 
Remember we don't have an unique way!

**Buy parts**

Input?
Output?

Considerations:
- we have a place to store items?
- we need a certain amount of parts in order not to stop production
- of course "1 part" is the mininum amount of parts to work with in the lean production
- can we assume we have a space to store the materials (like at least 1 week of material we use in production)  -> warehouse (1 week production parts)

- if you are a buyier what you have to do every day?

***

### Solution by professor (merged considerations)

    In quality memory of people is forbidden, if someone leaves we loose lots of informations.

- we could need management software, or read order in paper sheets


Input:
- customer DB: orders --> needed parts
- warehouse DB: (check if there are missing parts) [+ forecasts]
- supplier's register (contacts, info of reliability)

Providers:
- commercials (provide us the orders they received from clients)
- warehouse (warehouse management) for warehouse DB and supplier's register

Output:
- Buy order
- Warehouse DB

Customers: warehouse Dept. (they'll see that the parts are avaylable)

    Notes: always manage big orders by mail, so we get approval by manager. In case of misundertandings the resposibility is in the hands of the higher grade. Up to the company to decide from what budget to ask for approval.

We need a place to store all these informations.

Parameters:
- goals (come from deployment): how many days can I wait, we could forecast some orders (like slow shipment items)
    - acquire parts 1 week avg. no more than 2 weeks
    - ? profit maximization
- measurements
    - % delayed orders: (average delay amount of order)
    - 

we need ERP (Enterprise Resource Planner)

we can incentivate the goal reaching by splitting the salary in two parts, one fixed, the other variable

- 
- 

Goal: buy that part in order to 

[] Try to write sell items with this approach

# lecture 9
Trick: chain of responsibility has to be unbroken

### example 
How to fix a window? Who to call?
Who has the fault of a failure in design of an electronical device? C€ Fail (ue standard failed in a test by external)

-> we need cooperation between different areas in a company

# lecture 10

Organization chart

- lv1 Director
- lv2 Quality (many company do have)
- lv3 Commercial & marketing
- lv3 R&D
- lv3 Production
- lv3 Internal services

We may need an internal coordination between groups.

2 key concepts:
- Hand Off: like a wall that splits the responsibilities between areas
- Level: 

Try to write flowchart of activities, may include many people from many parts of a company.

If I have to verify something, the very best places in which I can add test, is when I move something between areas.

### example

We have a computer company which does:
- assembling computers
- install SW

If I have some problems from a missing part, also in SW I can sense the problem. Who has the fault of the error.

### Example table making (construction area, painting area)

block scheme:
[Construction]  ---(hand off)---> [painting]

If painting area does a checkpoint:
- qc (quality control) check: pass of fail

? try to look at the process of a customer asking for a number of a computer


commercial:
production:
research & development:
inner services:

1000 pcs
1000 videoprojectors
1000 hd cameras

phone contact


date of avayability
cost (material+people)

approval step to director (signature) [verification, or aother names]

[] exercise from this game we did in class (pc order from university)
//the whole exercise could have been sent in telegram group

# lecture 11
## Exercise: company that produces PCs, design an hand off (flowchart)

Some data to start
Input: order
Output: ready for delivery items
### our solution: on paper
[] copy it there

### Other solutions (+ professor)

(in) order
*design*: buy parts (deleted) if we have parts as input 
(in) parts (if we have this input)

*assembly*: assembly parts

*test*: test assembling

*sw*: install software 

*test*: test software

*inner services*: send pc

---
usually in warehouse there's an area in assembly to another dedicated area in software

different areas: indicates where the pc could be broken

- we could also split production outside the company (partners will do some steps)

---
### altra soluzione
 
(in) order
*design*: buy parts (deleted) if we have parts as input 
(in) parts (if we have this input)

*assembly*: assembly parts

*inner services*: store

*sw*: install sw

*inner services*: store

*test*: perform test then:
- Inner services : pc ready for delivery
- notification to commercial
- move back to the area (assembly or S/W) and track [to prevent]

*assembly*: assemble


Note: harder to predict the time if we have failures

activity of **improvement**: take logs from testing and perform action to take action and prevent the failures

Improvement:
review
IN: LOGS
OUT: PROPOSAL

The proposal goes back to direction
Could also be a proposal of changing the flow chart! (another phase of test, a repair area).

---
(in) order
*design*: buy parts (deleted) if we have parts as input 
(in) parts (if we have this input)

*assembly*: assembly  and store in inner area / or repair

*sw*: take assembly from assembly & install

*test*: perform test then:
- Inner services : pc ready for delivery
- notification to commercial
- move back to the area (assembly or S/W) and track [to prevent]

*assembly*: assemble

*inner services*: store parts & notify


# lecture 12

Standardization agencies could be two types (are quality ones so they're not mandatory)
- IEEE
- ISO 

CEN = translates EU directives (written by lawyers) into technical recommendations (those are MANDATORY)

We have to provide evidence that we are following a recommendation:
- conformance tests <- measure, record
- certification <- "exam"

- topic (eg. driving)
- exam
- authority
!!! no conflict of interests!!

Accredia --provides permission--> IQ NET, a club of companies
- private consulting
- exams -> to companies ISO 9001 (quality) 14001 (environment)


## Definition of quality
Quality = set of measurable properties that a product/service/process possesses to a certain degree, such as *reliability*, *consistency*, *performance*

    ISO 9000 definition of quality properties: 
    Ability in satisfying customers and relevant parties

What does it mean to satisfy customers?
Who are the customers I wish I have?


# lecture 13
Quality: ability to satisfy customer
Needs and relevant interested parties

* evidence -> written accessible

Fuctional test -> report (with valid data such as version, client, data, etc.)


Working rules + processes = manual of quality

Review - ask customer - data analytics - complaints
Endeca

people + processes + evidence + resources = management system (oriented to quality)

ISO 9001: certification
1st question: do your processes (written) fulfill min-requirements in ISO 9001?
2nd question: verify that written processes are really applied (check evidence)

# lecture 14 13/11/2023
## PDCA method 
The way company are certified.

If the action of a company are certified, they think also the product will be. Having a quality management system is intended to ensure quality

We may have some different kinds of management systems such as the *environmental management system*, a bit more popular these days.

9001--> quality
14001--> environment [you should track the energy consumption]

    **In exam:**
    no evidence of following a rule = rule not respected


Processes

1) RULES:
- mandatory laws
- ISO 9001
- company choices

Some examples: storage not in office, may cause fire. Doors have to be fire-resistant

What we need to do:
- **Design processes**: activity necessary. (preventive activity after incidents goes there)
- **keep under control**: ensure that goals are fulfilled with sufficient low variability (pre-defined). Need actions to correct. (can move people from a task to a critical one).

- corrective actions --> go into **Design Processes**
- review --> preventive action 

Also in a company we care about complaints (the more of these, the more probably we can loose a customer)
A generic complaint means nothing (like in the statement "we are always in delay!").
We need measurable statements ("12% of times we have a 1 day delay").

Some rules:
1) Measured statement
2) (new) Goal we can measure [we need thresholds]
3) Proposal --> modification to process (statement)
4) Experiment: perform an experiment in limited conditions (the experiment won't impact all the company, I need to engage like the best people/committed ones to participate to it). At the end of the experiment we "check".

    Check means: compare measurements with goals

5) Standardize: propagate to others the way
Propagate means modify if needed processes and then train people
We need to communicate the improvement to quality manager system, then I need money to spend on it.

The experiment has failed? Let's hear what was good and what was wrong. Start from beginning.

The numbers in the list before could be listed as follows:
- 1,2,3 the PLAN phase.
- 4 "Do" phase // so the experiment
- (right after 4) check // just after the experiment
- 5 "Act" phase. Some authors call it "standardize" instead of *act*

PDCA: acronymous of those 4 phases, indicates the method (Plan, Do, Check, Act)

## Exercise 1: Write a template for a Proposal of an Improvement Action.
Some companies tell to complainers to fill the template or stop complaining or equivalently "write a plan according to PDCA".
This is useful to formalize the complaint.

*Historical fact*: W. Eduards Deming was the inventor of this method. The PDCA is a continuous improvement tool.


## Exercise 2: write the process "continuos improvement".

If my company has not a quality standard, just propose it!

# lecture 15
## ADDED VALUE: important concept to add
Exercise: define ADDED VALUE



### Other solutions:
- difference between final price of a product and cost of materials & manufacturing
- attribute of a product found in a unique way
- increasing the benefit of the users
- trasformation of items into products having new properties/features
- any action/object that can up the price or the quality (excellence) of a service or a product

The way in which we perform an activity is also an advantage.

### Professor solution
(increase) is a process of the attitude/ability to satisfy a user need [Nota: la definizione formale è diversa, ma questa è utile]

ex: I like a color (he likes white, black is sad), so this feature makes perceive more value. Maybe another person doesn't like it, so it starts to become a fashion situation.

+ some companies do a portait of the typical user (gender, age, attitude, wishes, ..)

+ start from interface first when doing apps

+ process optimization: every action that does not provide added value to user could be avoided

How much testing do we need in a company?
We can have a degree of number of complaints and hours in testing.

We need to have a review activity that processes the complaints.

Recap: added value
- from economic point of view: added monetary value
- from quality point of view: satisfy some user's needs (or my company's needs)
What are they satisfied by? Try to delete all work activities that are not related to their satisfaction
Of course we cannot cut rules from governments (i.e. break the law).


# lecture 16 Documentation management
Document management phases:
1) kind of documents
2) life cycle/management (of documents)
Documenting means producing statements (dichiarazioni) about recommendations

It's important to UNDERSTAND the KIND of "DOCUMENTS" (1), to know how we do manage a document (regards its lifecycle) (2).

OUR PROPOSAL (1) inter-inner documentations, contracts, fatture, circulars, process documentations
(2) discussion --> written, reviewed (delivery) and published --> archived when not useful (physical or digital)

Other proposal:
(1) inner reports, contracts, product specifications, brochure, operation documents and reports

[]

# lecture 17

Argument of today: what to ask to director in order to get the quality certificate.

One duty of management is to write at least two documents:
1) Policy (that's a declaration)
    - "mission" of the company
    - should have a detail: "Policy for the quality": specific addendum explaining how will the quality will be pursued. The examiner will inspect all aspects (standard on end of life products), plans (improvement), also if the company measures parameters involved in the statements.
2) Service chart (ITALIAN:"carta dei servizi") 
    - declaration, numerical declaration of what is provided to customers. Usually numerical promises. As an examiner I will check if there are data to track what promised. (examples: refund policies in order to guarantee quality)


Policy needs to be stated because customer can select it based on its mission.
(should I optimize reliability, cheapness, fashion, ..)
When we open a company: find out your mission (what we are providing?)

## Find some ways to improve the culture

We have to do tricks to get people more sensitive about the quality.

Trick: we have lives, when we do something wrong we lose them and have a penalty

Another techinque is keeping a trasparent box with defected products.

Let be clear expected actions and responsibilities.
=> we will receive written request.

Organization chart should be public in the company.

### 1st exercise
take a company - write the mission. (just two sentences).
A plus would be to write also the Policy of quality.

### 2nd exercise
same company, write the service chart

Italian hospitals: each repart must have (by law) a service chart

### 3rd exercise
write an organization chart (choose dept, wirte expected arivities be perfomred in)

**Hint**: good idea is writing processes

Example: shoes company

activities:
- research (having ideas)
- design product and production line
- provisioning (get, acquire material) 
- production
- commercial (advertise, cotnracts)
- delivery
- ...


# lecture 18

## We need to do some stuff before getting a certification.

We will see some of the most mandatory stuff (there are many details mandatory too)

The standards comes from experienced workers.

Key point: understand the customers and propose something for them
Also have a clear comunication with the customer

## Commercial
- (*) communication. be sure that what we propose is understood. (can be techical, after they understood what it is we can start to be technical)
    - understand customers
    - explain mandatory rules
    - notify potential problems
    - verification 

Moral: Don't lie, don't wait, explain, as soon as you know notify

### example
We set a big order to a customer, but one of our suppliers runs out of businnes (and we are not getting in time):
-option a ) excuse to customer for the delay
-option b ) notify the delay *

Option b) is the best one for policy --> but then I have to deal with possible withdrawals


### exercise
A company produces management software, your customers are companies.
Enfasi: customers are industries (focused on production) !

To do:
- write the process "commercial offer"
    - from a top management view
    - also including handoff level (org. chart)
Q: how (*) are satisfied?

## Do a questionnaire to the customers!
What can I ask the customer, to understand if they are satisfied with our product?
if they dislike something, what it is? and why?

A good questionary have also a degree of importance of the questionary. *Like "how much the questionnaire is important to you?"*
Also we can put inside the questionnaire some "control" questions to see if the person is coherent. *We avoid some random compilers by putting a question A and its negative, to see if the answers are mirrored, as a coherent person will do.*

We need a **review** process for the compaints we receive.

## Review process
INPUT: complaints, or list of answer of customer surveys
OUTPUT: plan part of the pdca (or proposal/improvement action)

Customer surveys: provided by customer care and quality

# lecture 19

**Reminder**: this course is about how to modify activities in order to be complaint to the procedures

## design
Activity present in most of the companies.

Where we start and finish? From specs (a.k.a. design specifications)

All questions for a product are its specs (what is the purpose of our product, ..)

1- Also rules that are regulated by government are specs too

2- Some rules becomes mandatory in order to be compatible with some specification (choose to support some technology)

3- Inner rules: comes from past experience of a company (preferences, known problems, preferences and psicological preferences)

## Specs
> INPUT:
- user needs --> (tech specs)
- mandatory/recommended regulations
- company rules

> OUTPUT:
- tech construction files
    schematics, list of parts/materials
    source code (frozen version)
- manufacturing instructions
- (not product related but to mention) production line 


> Input providers:
- marketing/commercial
- Design (inner repositories) company knowledge (know how)
- external documentation sources

> Output providers
- production
- direction/management

Goal: do not traspose the order of deadline, avoid redesign

What's the value of a design?
- fulfill user needs
- easy in production
cost: people that do manifacturing and configuration

>QFD (quality function deployment)_> transform user needs into specs

We need to simulate some design, in electronics we use VHDL that will become the layout

usually...
-output specs becomes standards for simulations
-output simulations becomes standards for VHDL
-output VHDL becomes standards for layout 

one big problem in the stack is communication between layers

Process owner: supervisor of the whole stack, is an high role in a company

Portion of the salary in the stack worker can be distributed among workers but the process owner is the first person who is fired if the project failes.

Verification validation

Design is a process, each produce an instance of input, produces instance of output.

### exercise
provide specs of a product

tap 
- hot/cold water
- electrical valve / sensing flow, temperature
- wifi controler
- centralized control (like a hotel)
+ AI control

main activities needed for having the TCF (tech contruction files)

design phases/steps: specify resources needed

# lecture 04 12 23
lost
# lecture 06 12 23

Planning -> customer processes -> design & verification -> supply -> production

Quality means in brief.. have a contract, an agreement, quality is "be able to fulfill the agreement"

## example: problem with suppliers?
We need to:

Keep track --> Evaluating --> Rating

start to become a process..

- process: suppliers selection

I have then another process: continuous evaluation of suppliers <== "review"

The output is a "proposal of improvement".

- sometimes the design process has to be the fastest, to adapt to shortage of supply

- another process: verification of parts. WE CAN USE A MATH.RANDOM TO pick some parts with a certain series number (there are ISO rules too)

Inspecting product,.. is demanding.. we can instead choose to have a partner. Extra tests is done by the partner, in change of a discount.

fact: before becoming a partner go inspect the quantity of trash (products discarded from production line). If it's too much, don't become a partner, it's too costly and risky!

    Production: 
        test the product: when I design, and then at random after

    Monitoring (we must respect also some laws in certain products) 
    - capabilities of prod line
    - product specs
    - defects

some companies stop producing for a day for collecting proposals

managers have the responsibility to collect ideas

keep under control
prod. sproc.

preserve items

customer care

### exercise: computer shop company
write
- production process
- top management view
- handoff level
- define responsibilities
- define goals
- define & write "side processes" needed to
    - fullfill customer expectations 
    - requirements

# lecture 11 12 23

we have a company: pay taxes for at least one year

formal procedure: write processes
    
    respect the ISO recommendations
    how we solve the problem?
    how do we track?

we have to fulfill 9001 requirements

in practice is meaning months to do it..

after we have written the first version of processes we need a manual for the quality: we have policies, general view of the company and a list of processes.

    policy          top management view*
    processes -->   handhoff level (1)
                    detailed working instructions

*: significato dell'asterisco non detto
(1) helps the company understard the responsibilities

when the manual is ready, we can proceed to be examinated by inspectors

they will:
1) check conformity of the manual for the quality
2) audit (visit) usually two people or more if it is a big company. Also multisite verification is done if the company has many sites.
--> conformity of actions to written processes (they search for evidence)

.

    NON CONFORMITY= we wrote a rule but we did not respect it


What not to do: print the documents at last (they could notice a big amount of copies in the last day). Trick: put documents to the sun to let them be perceived as old and so trick inspectors [[dont do it please]].


Duration of the certificate: 6 months if it's fresh, 1 year if it's more expert

The reviewers for (like Accredia) the company has to be seen as people who are helping the company to stay alive.

Few months before companies perform an internal audit, just to prevent errors in the official

In the quality manager' calendar we have two dates:
- date for the external audit
- date for the internal audit

Where we start for checking? from the ones who I know don't respect the conformities

---
Once we have the cerfiticate we have other management systems we can aim to obtain.

14001 environment management system
    - we need to have processes
    - we would like to fulfill promises to the customer
    - we would respect also the laws

    --> environmental analysis is a table to fill with data
    like consumption of resources (energy, soil, water, air, ..)

    activity \ |  air, water,  pollution (water, noise, powders, CO2)

    --> improvement actions

    ES4= european project with lots of money involved

## risk analysis

Probability of something to be wrong.

We don't have to track everything..

Example: fire is a big risk

Risk analysis introduces another table to fill

Table involves consequence degree \ event (seen in Carel Presentation on pre-last lecture)

### example
A "fire" could have an high impact but it's probability could be small.

In the table we can color the cells indicating probability with colours, to identify the impact.
Then we can order the rows and columns of the table for high impact and high probability.

Review of the risk table (avoid bottom right corner!)

Plans & improvement actions, then upgrade the risk analysis

# 13/12 house of quality
slides on moodle

# 18/12 7 tools of quality
slides on moodle


# 20/12 business model generation (BMG)
(slide on moodle)

Type of companies (based on how a product is produced and distributed)

Chart for understanfing a company: canvas

Customer segments --> who are my customers

Customer relationships -->

Channels: trasportation --  need people

Revenue streams: where do we receive money for what

We can use our certification to make partnerships

Long tail: like ebay, that sells things out of maintainance

# quality - presentazione aziendale Carel (Bodo)

Carel - Bodo

slides may will be uploaded on moodle

# lecture 10 01 24

## Exam simulation (a company context could be also given)

Professor will choose companies close to computer science to let the exams be better understood by us.

Q1: define non conformity & classify kinds of
- write processes for management of non-conformities (T. M view)
- specify measurements


### Solution Q1:

3 kinds of situation:
- product Non conformity: when you violate a rule (P1)
- Process non conformities (P2)
- Non conformity to ISO 9001 presctiptions (P3)

**P1**

IN: observation/notification of product non conformity

PROVIDERS: "any"

OUT:
- fixed items (substituted, repaired, refunding)
- report

CLIENTS: 
- for external notifications the same people;
- for internal notifications "ANY";

MEASURE:
- € cost for fixing | Event
- number of non-conformities | Event
- time required to fix it | Event

**P2:**
IN: notification
(This notification is sent to a Proper inner inspector (better a manager of the employee responsible for the damage/non-conformity) So...)

PROVIDER: Inner Inpector (maybe in the Quality Department)

OUT:
- modified porcess design
- re-trained people

Clients would be people responsible of non-conformity

CLIENTS:
- QUALITY (b. of REDESIGN)
- HR (track of people)
- involved departments  IN NON-CONFORMITY

MEASUREMENTS:
- #occurrences
    - 1 dept (department)
    - 1 degree of severity:
        - don't know
        - don't want
        - you're fired

**(P3)**
IN: audit report

PROVIDER: auditor {internal/external}

OUT:
- Modified processes (manual for the quality) [we modify the quality manual]
- Retrained people
- new machinery (like if the non.conformity comes with our equipment)

CLIENTS: (in this case the top management)
- quality dep 
- direction
- involved department


Also a 4th process can be added, a PREVENTION one.

**P4** review of non conformities
IN: reports & measurements (from P1 and P2)
PROVIDERS: Quality
OUT: proposal for improvement action (plan for a PDCA loop)
DESCRIPTION: a commitee analyse the non-conformity reports attempting to discover prevention actions, in terms of a plan/proposal.

If we are certified: ask for a template!

## another exam question

Q2: Write process "management of a process non-conformity at the handoff level".

### answer Q2

Someone with higher experience check if people are not following the conformity.

Remember the tree of a company

              [DIR]
                |
                |-[Q]
    ------------------------
    |     |      |         |    
    [R&D] [PROD] [COMM] [Inn. services]  

Quality

    [Analyze non-conformity
    Involce interested parties
    Propose a solution]
        |
        |
        v
Dir

    [Approve solution
    acquire resources
    start the action]
        |
        |
        v 
Retraining
HR

    [training] 
        |
        |
        v
    Quality 
    [check]

or Quality 

    Apply prod, check


then I have the responsibility matrix.

    Action \ Department  |DIR| |Q| | Inner Services |
    ---------------------+---+-+-+-+----------------+
    Approval of solution | V | | | |                |
    ---------------------+---+-+-+-+----------------+
    Final check          |   | | |V|                |
    ---------------------+---+-+-+-+----------------+
    Plan                 |   | | |V|                |
    ---------------------+---+-+-+-+----------------+
    Training             |   | | | |       V        |
    ---------------------+---+-+-+-+----------------+
    Modify manual for QM | V | |V| |                |
    ---------------------+---+-+-+-+----------------+

(QM is quality management)

The added value of this process is perceived by the company.

CLIENTS: company itself

ADDED VALUE: rules to follow easy to understand and do the same job with less effort
More schematically ADDED VALUE is:
- inner company employee
- having processes well understood and easy to perform

To optimize the process we can delete the Director block in the chart (it's not creating value!). How we can delete it? With a new rule like "quality has XXX budget to act without explicit director approval". it is no more a waterfall flow, but it can work


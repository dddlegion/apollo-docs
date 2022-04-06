# Apollo Domain
## 1. Domain description
Selected domain for this project is a **Gaming tournaments management**. With this system users can schedule, follow
and attend gaming tournaments, create teams and communities, check the leaderboards and other fun stuff :)

## 2. Modules

### 2.1. User access
Each `Administrator`, `Participant`, ... is a `User`. To be a `User`, `User Registration` is required and should be confirmed.

Each `User` has one or more `User Role`.

Each `User Role` has a defined list of `Permissions`. A `Permission` defines whether `User` can have an access.

### 2.2. Administration
--\\--

### 2.3. Profile
Each `User` has `Profile` that contains general information about the `User` (name, surname, date of birth, `Profile Picture` etc.)

`User` can invite a `Friend`. Each `User` can have unlimited number of `Friends`.

`User` can create a `Team`. Each `User` can have unlimited number of `Teams`.
Each `Team` has a `Team Administrator` and `Team Members`. Default `Team Administrator` is a `User` who created a `Team`. `Team Administrator` is a `Team Member`
Count of `Team Members` can be limited for particular `Team`.

### 2.4. Tournaments
`User` can organize a `Tournament`. Each `Tournament` has an `Organizer`. 

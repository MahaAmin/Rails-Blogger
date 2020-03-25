# Ruby-On-Rails : Getting-Started-Notes

## Table Of Contents:
- Rails Philosophy
- Installing Rail
- Creating New Blog Application

## Rails Philosophy:
- **DRY Principle:** Do not Repeat Yourself. Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.
- **Convention Over Configuration:** Rails has opinions about the best way to do many things in a web application.

- Rails is an **MVC** mode:
    - **Model:**
    - **View:**
        - View templates are written in **eRuby** (Embedded Ruby).
    - **Controller:**

- **Routing:**
- **Action:**


## Installing Rails:
1. Check ruby is installed:
    ```sh
        ruby -v
    ```
2. Check sqlite3 is installed:
    ```sh
        sqlite3 --version
    ```
3. Install ruby development tools:
    ```sh
        sudo yum install ruby-devel
    ```
4. Install rails using gem:
    ```sh
        gem install rails
    ```
5. Check rails is installed:
    ```sh
        rails --version
    ```

## Creating New Blog Application:

- Default:
    ```sh
        rails new blog
    ```
- Using mysql:

    1. 
        ```
            rails new blog -d mysql 
        ```
    2. In **blog/config/database.yml**:
        ```
            development:
            adapter: mysql2
            database: your_db_name
            host: localhost
            username: your_mysql_user_name
            password: root's password
            encoding: utf8
        ```

- Installing dependencies:
    ```
        bundle install --path vendor/bundle
    ```

## Start Developing:

- Run developing server:
    ```
        rails server
    ```

### Models:

### Views:

### Controller:

- Create new controller "Welcome" with action called "index" :
    ```
        rails controller generate Welcome index
    ```

### Routes:

- Routes are configured in **config/routes.rb**.




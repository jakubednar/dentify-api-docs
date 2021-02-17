**Title**
----
  <_Additional information about your API call. Try to use verbs that match both request type (fetching vs modifying) and plurality (one vs multiple)._>

* **URL**

  <_The URL Structure (path only, no root url)_>

* **Method:**
  
  <_The request type_>

  `GET` | `POST` | `DELETE` | `PUT`
  
*  **URL Params**

   <_If URL params exist, specify them in accordance with name mentioned in URL section. Separate into optional and required. Document data constraints._> 

   **Required:**
 
   `id=[integer]`

   **Optional:**
 
   `photo_id=[alphanumeric]`

* **Data Params**

  <_If making a post request, what should the body payload look like? URL Params rules apply here too._>

* **Success Response:**
  
  <_What should the status code be on success and is there any returned data? This is useful when people need to to know what their callbacks should expect!_>

  * **Code:** 200 <br />
    **Content:** `{ id : 12 }`
 
* **Error Response:**

  <_Most endpoints will have many ways they can fail. From unauthorized access, to wrongful parameters etc. All of those should be liste d here. It might seem repetitive, but it helps prevent assumptions from being made where they should be._>

  * **Code:** 401 UNAUTHORIZED <br />
    **Content:** `{ error : 'Log in' }`

  OR

  * **Code:** 422 UNPROCESSABLE ENTRY <br />
    **Content:** `{ error : 'Email Invalid' }`

* **Sample Call:**

  <_Just a sample call to your endpoint in a runnable format ($.ajax call or a curl request) - this makes life easier and more predictable._> 

* **Notes:**

  <_This is where all uncertainties, commentary, discussion etc. can go. I recommend timestamping and identifying oneself when leaving comments here._> 

  ---
## H2 - Create the best documentation

### H3 - Create the best documentation
## H2 - Create the best documentation
> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_ **Markdown** into a blockquote.
 <_Additional information about your API call. Try to use verbs that match both request type (fetching vs modifying) and plurality (one vs multiple)._>

* ### URL

  <_The URL Structure (path only, no root url)_>
    ```
    200 OKFDE
    ```
    `fwefweefw`

* ### Method:
  
  <_The request type_>

  `GET` | `POST` | `DELETE` | `PUT`
  ```
    GET
  ```
*  **Data**
 
   `id=[integer]`
   ```
    No language indicated, so no syntax highlighting.
    But let's throw in a <b>tag</b>.
    ```
     ```js
    var validator = {
        id:'int'
    };
    var s = 'JavaScript syntax highlighting';
    alert(s);
    ```
    ```js
    const param = {
        patient_id:'exist, int'
    }
    const query = {}
    const body = {
        phone:'exist, string'
    }
    ```

* **Success Response:**
  
  <_What should the status code be on success and is there any returned data? This is useful when people need to to know what their callbacks should expect!_>

:::tip

**Code:** 200 OK <br />
**Code:**
```
200 OKFDE
```
**Content:** 
```js
{ 
    code: 200,
    msg: '',
    data: {
        teams:[{
            dentist:{
                title:string
                first_name:string
                last_name:string
                type:string
                email:string
                phone:string
	        }
            nurses:?[{
                title:'',
                first_name:'pwe',
                last_name:'pwe',
                type:'pwe',
                email:'pwe',
                phone:'pwe',
            }]
        }]
    }
 }
 ```

:::
 
* **Error Response:**

  <_Most endpoints will have many ways they can fail. From unauthorized access, to wrongful parameters etc. All of those should be liste d here. It might seem repetitive, but it helps prevent assumptions from being made where they should be._>

  * **Code:** 401 UNAUTHORIZED <br />
    **Content:** `{ error : 'Log in' }`

  OR

  * **Code:** 422 UNPROCESSABLE ENTRY <br />
    **Content:** `{ error : 'Email Invalid' }`



:::tip

This is a tip

:::

:::caution

This is a caution

:::

:::warning

This is a warning

:::

---

## POST /patient/:patient_id/tooth/:tooth_number/platform/procedure
> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_ **Markdown** into a blockquote.
 <_Additional information about your API call. Try to use verbs that match both request type (fetching vs modifying) and plurality (one vs multiple)._>

*  **Data**
 
   `id=[integer]`
   ```
    No language indicated, so no syntax highlighting.
    But let's throw in a <b>tag</b>.
    ```
     ```js
    var validator = {
        id:'int'
    };
    var s = 'JavaScript syntax highlighting';
    alert(s);
    ```
    ```js
    const param = {
        patient_id:'exist, int'
    }
    const query = {}
    const body = {
        phone:'exist, string'
    }
    ```

* **Success Response:**
  
  <_What should the status code be on success and is there any returned data? This is useful when people need to to know what their callbacks should expect!_>

:::tip

**Code:** 200 OK <br />
**Code:**
```
200 OKFDE
```
**Content:** 
```js
{ 
    code: 200,
    msg: '',
    data: {
        teams:[{
            dentist:{
                title:string
                first_name:string
                last_name:string
                type:string
                email:string
                phone:string
	        }
            nurses:?[{
                title:'',
                first_name:'pwe',
                last_name:'pwe',
                type:'pwe',
                email:'pwe',
                phone:'pwe',
            }]
        }]
    }
 }
 ```

:::
 
* **Error Response:**

  <_Most endpoints will have many ways they can fail. From unauthorized access, to wrongful parameters etc. All of those should be liste d here. It might seem repetitive, but it helps prevent assumptions from being made where they should be._>

  * **Code:** 401 UNAUTHORIZED <br />
    **Content:** `{ error : 'Log in' }`

  OR

  * **Code:** 422 UNPROCESSABLE ENTRY <br />
    **Content:** `{ error : 'Email Invalid' }`



:::tip

This is a tip

:::

:::caution

This is a caution

:::

:::warning

This is a warning

:::
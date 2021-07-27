
## API Reference

### Subjects
#### Get all subjects

```http
  GET /api/${campus}/subjects
```
#### Get a subject

```http
  GET /api/${campus}/subjects/${subject}
```
### Courses
#### Get all courses

```http
  GET /api/${campus}/courses
```
#### Get courses of a given the subject

```http
  GET /api/${campus}/courses/${subject}
```

 #### Get the course of a given subject and course number

```http
  GET /api/${campus}/courses/${subject}/${courseNumber}
```

 ### Sectons Information
 #### Get sections information

```http
  GET /api/${campus}/sections-info
```

 #### Get sections information of a given subject

```http
  GET /api/${campus}/sections-info/${subject}
```

 #### Get sections information of a given subject and course number

```http
  GET /api/${campus}/sections-info/${subject}/${courseNumber}
```

 #### Get section information of a given subject, course number, and section

```http
  GET /api/${campus}/sections-info/${subject}/${courseNumber}/${section}
```
 ### Historic Grades (thanks to UBCGrades.com)
 #### Get historic grades of a given subject 

```http
  GET /api/${campus}/grades/${session}/${subject}/${courseNumber}/${section}
```

 #### Get historic grades of a given subject and courseNumber 

```http
  GET /api/${campus}/grades/${session}/${subject}/${courseNumber}/${section}
```

 #### Get historic grades of a given subject, courseNumber, and section 

```http
  GET /api/${campus}/grades/${session}/${subject}/${courseNumber}/${section}
```

### Parameters

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `campus`      | `string` | **Required**. UBC Campus. Example: UBCO, UBCV |
| `session`      | `string` | **Required**. Session the course was offered. Example: 2020W, 2019S, 2019W| 
| `subject`      | `string` | **Required / Optional**. Course subject. Required for fetching historic grades, optional anywhere else. Example: COSC, CPSC, CHEM. |
| `courseNumber`      | `string` | **Optional**. Course number. Example: 111, 121, 530A| 
| `section`      | `string` | **Optional**. Course section. Example: 101, 001, 404A| 


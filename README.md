
<h2>UBC Time API</h2>
<h4>URL: ubctime.herokuapp.com/api <h4>

<table>
    <tr>
        <th>GET SUBJECTS</th>
        <th>GET COURSES</th>
        <th>GET SECTIONS INFO</th>
    </tr>
    <tr>
        <td>/:campus/subjects/:subject?</td>
        <td>/:campus/courses/:subject?/:courseNumber?</td>
        <td>/:campus/courses/:subject?/:courseNumber?/:section?</td>
    </tr>
    <tr>
        <td>/ubcv/subjects/</td>
        <td>/ubcv/courses</td>
        <td>/ubcv/sections-info/</td>
    </tr>
    <tr>
        <td>/ubco/subjects/cosc</td>
        <td>/ubco/courses/cosc/121</td>
        <td>/ubco/sections-info/cosc/121/101</td>
    </tr>
  </table>

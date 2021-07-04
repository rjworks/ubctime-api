
<h2>UBC Time API</h2>
<h4>URL: ubctime.herokuapp.com/api <h4>

<table>
    <tr>
        <th>GET SUBJECTS</th>
        <th>GET COURSES</th>
        <th>GET SECTIONS INFO</th>
        <th>GET HISTORIC GRADES (thanks to UBCGrades.com)</th>
    </tr>
    <tr>
        <td>/:campus/subjects/:subject?</td>
        <td>/:campus/courses/:subject?/:courseNumber?</td>
        <td>/:campus/courses/:subject?/:courseNumber?/:section?</td>
        <td>/:campus/grades/:session/:subject/:courseNumber?/:section?</td>
    </tr>
    <tr>
        <td>/ubcv/subjects/</td>
        <td>/ubcv/courses</td>
        <td>/ubcv/sections-info/</td>
        <td>/ubcv/grades/2020W/cpsc/</td>
    </tr>
    <tr>
        <td>/ubco/subjects/cosc</td>
        <td>/ubco/courses/cosc/121</td>
        <td>/ubco/sections-info/cosc/121/101</td>
        <td>/ubco/grades/2019S/cosc/121/101</td>
    </tr>
  </table>

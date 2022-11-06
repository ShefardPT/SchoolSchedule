<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

API for school schedule management.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

*TBD*

### Installation

*TBD*

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [ ] Implement CRUD for entities (schools, teachers, students, grades, subjects, schedules)
	- [ ] Base logics
- [ ] Swagger Docs
- [ ] Init DB Migration
- [ ] Cover logics with unit tests
- [ ] Additional logics
	- [ ] Additional params:
		- [ ] Take into account the number of school shifts for the school when creating classes and schedules.
		- [ ] Take into account the minimum and maximum number of lessons per shift for the school, class, teacher.
		- [ ] Take into account the required grade or range of grades for school subjects.
		- [ ] Take into account the possibility of teachers to work part-time in several schools on different days when creating timetables.
		- [ ] Take into account the required grade or range of school grades in which the teacher can teach.
		- [ ] Implement the ability to set the duration of lessons and breaks for the school and / or classes, taking into account these parameters when creating schedules.
		- [ ] Account for holidays.
	- [ ] Implement the ability to display the schedule(s) for the class(s) / teacher(s) / student(s)/ schools(s).
	- [ ] Implement the mechanism of grading with the calculation of the average score for the student /class / school / teacher on a specific subject.
	- [ ] Implement the mechanism of registration of visits to lessons.
	- [ ] Implement the mechanism of automatic transfer of a student to the next class, subject to the conditions of attendance and the minimum score
	- [ ] Implement the output of entities should be filtered by the parameters available to the entity (specific value(s), range of values, 'like'-filtering, greater/less, greater/less or equal).
	- [ ] Implement the output of both one entity and a list output with a specified pagination step (e.g. output of 10/25/50 entities at a time with the display of the current page and the total number of entities and pages at the current pagination step) with the possibility of ordering in forward or reverse order by one or more specified fields.
	- [ ] Implement automatic and manual creation of school schedules.
	- [ ] Implement a flexible schedule generator.
	- [ ] Implement a method for generating schedule variants (e.g. if the schedule variation is not the only possible one) with the ability to save this schedule variant for a specific class, which will be taken into account when generating schedules for other classes.
	- [ ] Implement a method for generating schedule options simultaneously for all school classes for a given academic period with the ability to save one, several or all schedules for the academic period.
	- [ ] Implement a method to generate schedule options simultaneously for all classes of several or all schools for a given academic period with the ability to save several or all schedules for the academic period of several or all schools at once.
	- [ ] Implement entities CRUD validation.
	- [ ] Implement authentication. 
	- [ ] Implement authorization. 

See the [open issues](https://github.com/ShefardPT/SchoolSchedule/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
<!--## License

Distributed under the ??? License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
-->


<!-- CONTACT -->
## Contact

Shefer Alexander - [@LinkedIn](https://www.linkedin.com/in/alexander-shefer-392774177/) - shefard.aa@gmail.com

Project Link: [https://github.com/ShefardPT/SchoolSchedule](https://github.com/ShefardPT/SchoolSchedule)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

<!--* []()
* []()
* []()
-->

<p align="right">(<a href="#readme-top">back to top</a>)</p>

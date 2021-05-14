<template>
  <div class="gallery grey lighten-4">
    <v-parallax
      class="para"
      style="height: 200px; opacity: 1"
      gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.9)"
      dark
      src="../assets/6.jpg"
    >
      <v-overlay value="true" absolute>
        <v-row align="center" justify="center">
          <v-col class="text-center" cols="12">
            <h1 class="display-1 font-weight-thin mb-4"><b>Profile</b></h1>
          </v-col>
        </v-row>
      </v-overlay>
    </v-parallax>

    <v-container class="hidden-xs-only">
      <v-row class="pa-15 pt-8 pb-8">
        <v-col cols="2" xs="2" sm="2" md="2">
          <v-card color="transparent" class="pa-2">
            <v-card>
              <v-img src="../assets/ernest.jpg" style="height: 150px"></v-img>
            </v-card>
          </v-card>
        </v-col>

        <v-col cols="10" xs="10" sm="10" md="10" class="pt-14">
          <v-row class="pt-3"> <h3>ERNEST KWAME AMUZU</h3> </v-row>
          <v-row class="pt-3"> <h3>QA ENGINEER</h3></v-row>
          <v-row class="pt-3"
            >Self-motivated Quality Assurance Engineer. I have a lot of
            experience in developing test cases and testing and verification of
            software. I aspire to be one of the top Software Engineers globally
            in the next five (5) years.</v-row
          >
        </v-col>
      </v-row>

      <v-row class="pl-14 pt-0 mt-0 ml-1">
        <v-col cols="7" xs="7" sm="7" md="7">
          <v-row> <h3 style="text-decoration: underline">Education</h3> </v-row>
          <v-row>
            <h4>Graduate Trainee (Software Testing and Verification)</h4>
          </v-row>
          <v-row><p>AmaliTech Training Academy</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2019 - 2020</i></p></v-row
          >

          <v-row>
            <h4>Diploma in Information Technology (Software Engineering)</h4>
          </v-row>
          <v-row><p>AmaliTech Training Academy</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2017 - 2019</i></p></v-row
          >

          <v-row>
            <h4>B.A Integrated Rural Art and Industry</h4>
          </v-row>
          <v-row
            ><p>Kwame Nkrumah University of Science and Technology</p>
          </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2011 - 2015</i></p></v-row
          >

          <v-row>
            <h4>Certificate in Computer Literacy (Graphic Design)</h4>
          </v-row>
          <v-row><p>Imperial College of Professional Studies</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2011</i></p></v-row
          >

          <v-row>
            <h4>West African Senior School Certificate</h4>
          </v-row>
          <v-row><p>KNUST Senior High School</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2007 - 2011</i></p></v-row
          >

          <v-row>
            <h4>Certificate in Computer Literacy</h4>
          </v-row>
          <v-row
            ><p>Kumasi Virtual Centre for Information Technology, KNUST</p>
          </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2007</i></p></v-row
          >

          <v-row>
            <h3 style="text-decoration: underline">Work Experience</h3>
          </v-row>
          <v-row>
            <h4>Dr. T-bone Services</h4>
          </v-row>
          <v-row
            ><p>
              Assistant craftsman in Welding and Fabrication processes
              (Industrial Attachment)
            </p>
          </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2014</i></p></v-row
          >

          <v-row>
            <h4>Tsito Senior High Technical School</h4>
          </v-row>
          <v-row><p>Assistant Storekeeper (National Service)</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2015 - 2016</i></p></v-row
          >

          <v-row>
            <h4>Ghana Statistical Service</h4>
          </v-row>
          <v-row><p>Lister (Multiple Indicator Cluster Survey)</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2017</i></p></v-row
          >

          <v-row>
            <h4>
              Centre for Scientific and Industrial Research (Wood Industry and
              Utilization Division)
            </h4>
          </v-row>
          <v-row><p>Assistant (EPA BAMBOO TRANSPLANTING PROJECT)</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2016-2017</i></p></v-row
          >

          <v-row>
            <h4>Ghana Statistical Service</h4>
          </v-row>
          <v-row><p>Enumerator (Agric Census)</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2018</i></p></v-row
          >

          <v-row>
            <h4>National Board for Small Scale Industries (NABCO)</h4>
          </v-row>
          <v-row><p>Administrative Staff</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2018 - 2019</i></p></v-row
          >

          <v-row>
            <h3 style="text-decoration: underline">Personal Information</h3>
          </v-row>
          <v-row>
            <v-col cols="6"><p>Location</p></v-col>
            <v-col cols="6" class="float-right"><p>Takoradi, Ghana</p></v-col>
          </v-row>

          <v-row>
            <v-col cols="6"><p>Email</p></v-col>
            <v-col cols="6" class="float-right"
              ><p>ernestamuzu@ymail.com</p></v-col
            >
          </v-row>

          <v-row>
            <v-col cols="6"><p>LinkedIn</p></v-col>
            <v-col cols="6" class="float-right"
              ><p>
                <a href="www.linkedin.com/in/ernest-amuzu">
                  www.linkedin.com/in/ernest-amuzu
                </a>
              </p></v-col
            >
          </v-row>

          <v-row>
            <v-col cols="6"><p>Facebook</p></v-col>
            <v-col cols="6" class="float-right"
              ><p>
                <a href="facebook.com/ernest.amuzu"
                  >facebook.com/ernest.amuzu</a
                >
              </p></v-col
            >
          </v-row>

          <v-row>
            <v-col cols="6"><p>LinkedIn</p></v-col>
            <v-col cols="6" class="float-right"
              ><p>
                <a href="www.linkedin.com/in/ernest-amuzu">
                  www.linkedin.com/in/ernest-amuzu
                </a>
              </p></v-col
            >
          </v-row>

          <v-row>
            <v-col cols="6"><p>GitHub</p></v-col>
            <v-col cols="6" class="float-right"
              ><p>
                <a href="www.linkedin.com/in/ernest-amuzu">
                  www.github.com/calliernie</a
                >
              </p></v-col
            >
          </v-row>
        </v-col>

        <v-divider vertical class="my-6"></v-divider>

        <v-col cols="5" xs="5" sm="5" md="5">
          <v-row class="pl-8">
            <h3 style="text-decoration: underline">Skills</h3>
          </v-row>
          <v-row class="pl-5">
            <v-col cols="12">
              <p>Excellent written communication skills</p>
              <p>Swift Decision Making</p>
              <p>Self-motivation</p>
              <p>Teamwork</p>
              <p>Creativity</p>
              <p>Ability to work under pressure</p>
              <p>Great presentation skills</p>
            </v-col>
          </v-row>

          <v-row class="pl-8">
            <h3 style="text-decoration: underline">Languages</h3>
          </v-row>
          <v-row class="pl-5">
            <v-col cols="12">
              <p>Java (Intermediate)</p>
              <p>SQL (Intermediate)</p>
              <p>HTML (Proficient)</p>
              <p>Javascript (Beginner)</p>
              <p>CSS (Proficient)</p>
              <p>PHP (Intermediate)</p>
              <p>JUnit (Beginner)</p>
              <p>Selenium (Beginner)</p>
            </v-col>
          </v-row>

          <v-row class="pl-8">
            <h3 style="text-decoration: underline">Design Softwares</h3>
          </v-row>
          <v-row class="pl-5">
            <v-col cols="12">
              <p>Photoshop (Proficient)</p>
              <p>Rhinoceros 3D (Proficient)</p>
              <p>After Effects (Intermediate)</p>
              <p>Keyshot (Proficient)</p>
              <p>Adobe XD (Proficient)</p>
            </v-col>
          </v-row>

          <v-row class="pl-8">
            <h3 style="text-decoration: underline">Interests</h3>
          </v-row>
          <v-row class="pl-5">
            <v-col cols="12">
              <p>Reading</p>
              <p>Digital Painting</p>
              <p>Listening to music</p>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>

    <v-container class="hidden-sm-and-up">
      <v-row class="px-4">
        <v-col cols="12" xs="12" sm="2" md="2">
          <v-card class="mx-auto" max-width="">
            <v-img
              height="300"
              src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
            ></v-img>
          </v-card>
        </v-col>

        <v-col cols="12" xs="12" sm="10" md="10" class="px-6">
          <v-row class="pt-1"> <h3>ERNEST KWAME AMUZU</h3> </v-row>
          <v-row class="pt-1"> <h3>QA ENGINEER</h3></v-row>
          <v-row class="pt-1"
            >Self-motivated Quality Assurance Engineer. I have a lot of
            experience in developing test cases and testing and verification of
            software. I aspire to be one of the top Software Engineers globally
            in the next five (5) years.</v-row
          >
        </v-col>
      </v-row>

      <v-row class="px-7 pt-4">
        <v-col cols="12" xs="12" sm="7" md="7">
          <v-row> <h3 style="text-decoration: underline">Education</h3> </v-row>
          <v-row>
            <h4>Graduate Trainee (Software Testing and Verification)</h4>
          </v-row>
          <v-row><p>AmaliTech Training Academy</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2019 - 2020</i></p></v-row
          >

          <v-row>
            <h4>Diploma in Information Technology (Software Engineering)</h4>
          </v-row>
          <v-row><p>AmaliTech Training Academy</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2017 - 2019</i></p></v-row
          >

          <v-row>
            <h4>B.A Integrated Rural Art and Industry</h4>
          </v-row>
          <v-row
            ><p>Kwame Nkrumah University of Science and Technology</p>
          </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2011 - 2015</i></p></v-row
          >

          <v-row>
            <h4>Certificate in Computer Literacy (Graphic Design)</h4>
          </v-row>
          <v-row><p>Imperial College of Professional Studies</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2011</i></p></v-row
          >

          <v-row>
            <h4>West African Senior School Certificate</h4>
          </v-row>
          <v-row><p>KNUST Senior High School</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2007 - 2011</i></p></v-row
          >

          <v-row>
            <h4>Certificate in Computer Literacy</h4>
          </v-row>
          <v-row
            ><p>Kumasi Virtual Centre for Information Technology, KNUST</p>
          </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2007</i></p></v-row
          >

          <v-row>
            <h3 style="text-decoration: underline">Work Experience</h3>
          </v-row>
          <v-row>
            <h4>Dr. T-bone Services</h4>
          </v-row>
          <v-row
            ><p>
              Assistant craftsman in Welding and Fabrication processes
              (Industrial Attachment)
            </p>
          </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2014</i></p></v-row
          >

          <v-row>
            <h4>Tsito Senior High Technical School</h4>
          </v-row>
          <v-row><p>Assistant Storekeeper (National Service)</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2015 - 2016</i></p></v-row
          >

          <v-row>
            <h4>Ghana Statistical Service</h4>
          </v-row>
          <v-row><p>Lister (Multiple Indicator Cluster Survey)</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2017</i></p></v-row
          >

          <v-row>
            <h4>
              Centre for Scientific and Industrial Research (Wood Industry and
              Utilization Division)
            </h4>
          </v-row>
          <v-row><p>Assistant (EPA BAMBOO TRANSPLANTING PROJECT)</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2016-2017</i></p></v-row
          >

          <v-row>
            <h4>Ghana Statistical Service</h4>
          </v-row>
          <v-row><p>Enumerator (Agric Census)</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2018</i></p></v-row
          >

          <v-row>
            <h4>National Board for Small Scale Industries (NABCO)</h4>
          </v-row>
          <v-row><p>Administrative Staff</p> </v-row>
          <v-row class="pt-0 mt-0"
            ><p><i>2018 - 2019</i></p></v-row
          >

          <v-row>
            <h3 style="text-decoration: underline">Personal Information</h3>
          </v-row>
          <v-row class="pr-3">
            <p>Location</p>
            <v-spacer></v-spacer>
            <p>Takoradi, Ghana</p>
          </v-row>

          <v-row class="pr-3">
            <p>Email</p>
            <v-spacer></v-spacer>
            <p>ernestamuzu@ymail.com</p>
          </v-row>

          <v-row class="pr-3">
            <p>LinkedIn</p>
            <v-spacer></v-spacer>
            <p>
              <a href="www.linkedin.com/in/ernest-amuzu">
                www.linkedin.com/in/ernest-amuzu
              </a>
            </p>
          </v-row>

          <v-row class="pr-3">
            <p>Facebook</p>
            <v-spacer></v-spacer>
            <p>
              <a href="facebook.com/ernest.amuzu">
                www.linkedin.com/in/ernest-amuzu
              </a>
            </p>
          </v-row>

          <v-row class="pr-3">
            <p>GitHub</p>
            <v-spacer></v-spacer>
            <p>
              <a href="www.linkedin.com/in/ernest-amuzu">
                www.linkedin.com/in/ernest-amuzu
              </a>
            </p>
          </v-row>

          <v-row>
            <h3 style="text-decoration: underline">Skills</h3>
          </v-row>
          <v-row class="pr-3">
            <p>Excellent written communication skills</p>
          </v-row>
          <v-row class="pr-3">
            <p>Swift Decision Making</p>
          </v-row>
          <v-row class="pr-3">
            <p>Self-motivation</p>
          </v-row>
          <v-row class="pr-3">
            <p>Teamwork</p>
          </v-row>
          <v-row class="pr-3">
            <p>Creativity</p>
          </v-row>
          <v-row class="pr-3">
            <p>Ability to work under pressure</p>
          </v-row>
          <v-row class="pr-3">
            <p>Great presentation skills</p>
          </v-row>

          <v-row>
            <h3 style="text-decoration: underline">Languages</h3>
          </v-row>
          <v-row class="pr-3">
            <p>Java (Intermediate)</p>
          </v-row>
          <v-row class="pr-3">
            <p>SQL (Intermediate)</p>
          </v-row>
          <v-row class="pr-3">
            <p>HTML (Proficient)</p>
          </v-row>
          <v-row class="pr-3">
            <p>Javascript (Beginner)</p>
          </v-row>
          <v-row class="pr-3">
            <p>CSS (Proficient)</p>
          </v-row>
          <v-row class="pr-3">
            <p>PHP (Intermediate)</p>
          </v-row>
          <v-row class="pr-3">
            <p>JUnit (Beginner)</p>
          </v-row>
          <v-row class="pr-3">
            <p>Selenium (Beginner)</p>
          </v-row>

          <v-row>
            <h3 style="text-decoration: underline">Design Softwares</h3>
          </v-row>
          <v-row class="pr-3">
            <p>Photoshop (Proficient)</p>
          </v-row>
          <v-row class="pr-3">
            <p>Rhinoceros 3D (Proficient)</p>
          </v-row>
          <v-row class="pr-3">
            <p>After Effects (Intermediate)</p>
          </v-row>
          <v-row class="pr-3">
            <p>Keyshot (Proficient)</p>
          </v-row>
          <v-row class="pr-3">
            <p>Adobe XD (Proficient)</p>
          </v-row>

          <v-row>
            <h3 style="text-decoration: underline">Interests</h3>
          </v-row>
          <v-row class="pr-3">
            <p>Reading</p>
          </v-row>
          <v-row class="pr-3">
            <p>Digital Painting</p>
          </v-row>
          <v-row class="pr-3">
            <p>Listening to music</p>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<style scoped>
.gallery {
  width: 100%;
  height: 100%;
  /* background-image: url("../assets/background.png"); */
  background-size: cover;
  background-position: center;
  position: relative;
  overflow: hidden;
}

.transparent {
  height: 170px;
}

.innerCard {
  height: 185px;
}

.img {
  height: 185px;
}
/* .outCard {
  background-color: transparent !important;
  border-color: transparent !important;
} */
</style>

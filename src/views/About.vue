<template>
  <mdb-container fluid>
    <!-- Section: Create Page -->
    <section class="section mt-5">
      <!-- First row -->
      <mdb-row> 
        <mdb-col>
          <div class="card mb-4 post-title-panel">
            <div class="card-body mslide">
                <h1>Welcome to Law204-Law of Contract II </h1>
                <p>
                    LAW203 is a pre-requisite for this course. After having completed the LAW203 Module, 
                    you are expected to appreciate and understand the fundamental principles of the law 
                    of contract and their application in the resolution of contractual disputes. LAW203 
                    covered the formation of valid and legally enforceable agreements, the principles of 
                    offer and acceptance, forms of contract, the essential elements of a valid contract, 
                    the legal effect of various vitiating factors, and the discharge of a contract.
                </p>

                <div id="moduleOverView">
                    <h3>Module Overview</h3>
                    <p>
                        LAW204 takes you further on specific principles of the law of contract. This 
                        module covers contractual warranties and conditions; variations; waivers; 
                        specific types of contracts, performance; termination; breach of contract; remedies
                        and an introduction to the basic principles of drafting of a contract.
                    </p>
                    <p>
                        Please note that as a law student, it is imperative that you study legislation, 
                        case law and academic literature. All units will be discussed with reference to these
                        resources, and you are expected to read all with understanding and be in a position 
                        to apply the principles to any given set of facts.
                    </p>
                    <p>
                        In this module, you will cover a total of eight (8) Units which will have various activities
                    </p>

                </div>
                
                    <div id="studySkills" class="note "> 
                    <p>
                        As an adult learner your approach to learning will be different to that from your school days: 
                        you will choose what you want to study, you will have professional and/or personal motivation
                        for doing so and you will most likely be fitting your study activities around other professional 
                        or domestic responsibilities.
                    </p>
                    <p>
                        Essentially you will be taking control of your learning environment. As a consequence, you will
                        need to consider performance issues related to time management, goal setting, stress management, 
                        etc. Perhaps you will also need to reacquaint yourself in areas such as essay planning, coping with
                        exams and using the web as a learning resource.
                    </p>
                    <p>
                        Your most significant considerations will be time and space i.e. the time you dedicate to your 
                        learning and the environment in which you engage in that learning.
                    </p>
                    <p>
                        We recommend that you take time now—before starting your self-study—to familiarize yourself with these issues. 
                        There are a number of excellent resources on the web. A few suggested links are:
                        <ul>
                            <li>
                                <a href="http://www.how-to-study.com/">http://www.how-to-study.com/</a>
                                <p>
                                The “How to study” web site is dedicated to study skills resources. You will find links to study 
                                preparation (a list of nine essentials for a good study place), taking notes, strategies for 
                                reading text books, using reference sources, test anxiety. 
                                </p>
                            </li>
                            <li>
                                <a href="http://www.ucc.vt.edu/stdysk/stdyhlp.html">http://www.ucc.vt.edu/stdysk/stdyhlp.html</a>
                                <p>
                                This is the web site of the Virginia Tech, Division of Student Affairs. You will find links to 
                                time scheduling (including a “where does time go?” link), a study skill checklist, basic concentration 
                                techniques, control of the study environment, note taking, how to read essays for analysis, memory skills 
                                (“remembering”). 
                                </p>
                            </li>
                            <li>
                                <a href="http://www.howtostudy.org/resources.php">http://www.howtostudy.org/resources.php</a>
                                <p>
                                    Another “How to study” web site with useful links to time management, efficient reading, questioning/listening/observing 
                                    skills, getting the most out of doing (“hands-on” learning), memory building, tips for staying motivated,
                                    developing a learning plan.
                                </p>
                            </li>
                        
                        </ul>
                        
                        The above links are our suggestions to start you on your way. At the time of writing these web links were active. If you want to look for more go to <a href="www.google.com">google</a> and type “self-study basics”, “self-study tips”, “self-study skills” or similar.
                        
                    </p>
                </div>
            </div>
          </div>
        </mdb-col>
      </mdb-row>
      <!-- /.First row -->
    </section>
    <!-- /.Section: Create Page -->
  </mdb-container>
</template>

<script>
import {
  mdbContainer
} from "mdbvue";

export default {
  name: "About",
  components: {
    mdbContainer
  },
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.mslide{
  background-color: #e1f5fe;
  
}
</style>

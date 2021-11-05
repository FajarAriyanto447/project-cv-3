<template>
  <div>
    <div class="pap">
      <div class="flex-container">
        <div>RESUME</div>
      </div>
      <div style="display: flex">
        <h1>
          <img
            src="https://www.novisetianurviat.com/images/comp/novi.jpg"
          />FAJAR ARIYANTO
        </h1>
      </div>
    </div>
    <body v-for="user in ListCv" :key="user">
      <div style="display: flex" class="app">
        <div class="op">
          <h2>
            PROFIL
            <hr />
          </h2>
          <p>
            <b>NAMA</b><br />
            Fajar Ariyanto
          </p>
          <p>
            <b>TANGGAL LAHIR</b><br />
            09 Mei 2006
          </p>
          <b>ALAMAT</b><br />
          Tambaksari,Rt05/Rw06, Sruni, Musuk, Boyolali<br /><br />
          <b>WEBSITE</b><br />
          <u>fajarariyanto.com</u><br /><br />

          <h3>
            PENGHARGAAN
            <hr />
          </h3>

          <b>PENGHARGAAN KREATIF 2012</b> <br />
          Openminded.org <br /><br />
          <b>DESAIN ANTARMUKA 2013</b> <br />
          Coolideas.com <br />

          <h3>
            KONTAK
            <hr />
          </h3>
          <b>NOMOR RUMAH</b> &#9742; <br />
          (0411) 123 456 <br /><br />

          <b>NOMOR TELEPON</b> &#128222;<br />
          0821 9530 7133 <br /><br />

          <b>EMAIL</b> &#128386;<br />
          fajarariyanto447@gmail.com<br />

          <h3>
            SOSIAL
            <hr />
          </h3>
          <b>TWITER</b> <br />
          @Fajar_ariyanto <br /><br />

          <b>FACEBOOK</b> <br />
          Fajar_ariyanto <br /><br />
        </div>
        <div class="pp">
          <h2>
            SENIMAN GRAFIS
            <hr />
          </h2>
          <div id="app">
            <h3>
              &#128092;  WORK EXPERIENCE
              <hr />
            </h3>
            <div style="column-count: 2">
              <p>
                <b>TEKNIK KOMPUTER & JARINGAN</b><br />
                Jul 2021-Mar 2024
              </p>
              <br />
              <p>
                <b>BOOTCAMP / CODING</b><br />
                Okt 2021-Mei 2022
              </p>
              <br />

              <b>SMK Bina Nusantara Semarang</b><br />Semarang, Indonesia
              <br /><br /><br />
              <b>SMK Bina Nusantara Semarang</b><br />Semarang, Indonesia
              <br /><br /><br />
            </div>
          </div>
          <br />
          <div id="ppa">
            <h3>&#128213;  PENDIDIKAN</h3>
            <hr />
            <div style="column-count: 2">
              <b>MASTER DEGREE</b><br />Feb 2011-Jun 2014 <br /><br />
              <b>MASTER DEGREE</b><br />Feb 2011-Jun 2014 <br /><br />
              <b>MASTER DEGREE</b><br />Feb 2011-Jun 2014 <br /><br />

              <b>SMK Bina Nusantara Semarang</b><br />Semarang, Indonesia
              <br /><br />
              <b>SMK Bina Nusantara Semarang</b><br />Semarang, Indonesia
              <br /><br />
              <b>SMK Bina Nusantara Semarang</b><br />Semarang, Indonesia
              <br /><br />
            </div>
          </div>
          <br />
          <div id="opo">
            <h3> &#128161;  KEAHLIAN</h3>
            <hr />
            <div style="column-count:2">
              <p><b>PROFESSIONAL SKILLS</b></p>
              <div style="column-count: 2">
                Microsoft Windows 
                <p>Windows  </p>
                <p>mac OSX</p>
                <p>Data Headling</p>
                <p>Record Kepping</p>
                <p>Web Skills</p>

              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p>
              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p>
              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p>
              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p>
              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p>
              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p>
              </div>
                
               <p><b>PERSONAL</b></p>
              <div style="column-count:2">
                <p>Organistion   </p>   
                <p>Communication</p>
                <p>Time Keeping</p>
                <p>Team Player</p>
                <p>Commitment</p>
                <p>Multitasking</p>

                <p>.</p>
              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p> 
              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p> 
              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p> 
              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p> 
              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p> 
              <p>&#9899;&#9899;&#9899;&#9899;&#9899;<span style="opacity:0.5">&#9899;&#9899;</span></p> 

            </div>
            </div>
          </div>
        </div>
      </div>
    </body>
  </div>
</template>
<script>
import axios from "axios";
export default {
  name: "ListCv2",
  data() {
    return {
      ListCv: [],
    };
  },
  mounted() {
    this.load();
  },
  methods: {
    load() {
      axios
        .get(" http://localhost:3000/ListCv")
        .then((res) => {
          this.ListCv = res.data;
        })
        .catch((err) => {
          console.log(err);
        });
    },
  },
};
</script>
<style scoped>
body {
  /* font-family: "Courier New", Courier, monospace; */
}
.op {
  background-color: whitesmoke;
  border-radius: 1px;
  position: relative;
  width: 300px;
  border: 2px;
  padding: 20px;
  text-align: right;
}
#app {
  background-color: rgb(202, 197, 197);
  border-radius: 5px;
  width: 650px;
  border: 2px;
  padding: 20px;
}
.flex-container {
  display: flex;
  background-color: white;
  color: whitesmoke;
  border-radius: 0px;
}
.flex-container > div {
  background-color:  rgb(0, 0, 63);
  margin: 0px;
  padding: 0px;
  margin-left: 80px;
}
#ppa {
  background-color: rgb(202, 197, 197);
  border-radius: 5px;
  width: 650px;
  border: 2px;
  padding: 20px;
  margin-top: 25px;
}
#opo {
  background-color: rgb(202, 197, 197);
  border-radius: 5px;
  width: 650px;
  border: 2px;
  padding: 20px;
}
.A {
  background-color: white;
  color: black;
  margin-left: 20px;
}

.pp {
  background-color: whitesmoke;
  border-radius: 1px;
  position: relative;
  width: 700px;
  border: 2px;
  padding: 20px;
}

img {
  width: 170px;
  border-radius: 50%;
  background-color: yellow;
  float: top;
  border: 8px solid whitesmoke;
  
}
p,
ul,
li {
  font-size: 15px;
}
.pap {
  padding: 20px;
  margin-right: 249px;
  color: whitesmoke;
  background-color: rgb(0, 0, 63);
}
hr {
  border-top: 2px dotted black;
}
h3{
  font-family: 'Courier New', Courier, monospace;
}
</style>
<template>
  <v-container fluid>
    <v-text-field clearable id="Text"></v-text-field>
    <v-col cols="12" v-bind:class="{ mirror: isActive }">
      <v-row justify="center">
        <v-btn color="success" fab dark @click="changeText('A')">
          <v-img :src="require('../assets/A.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('B')">
          <v-img :src="require('../assets/B.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('C')">
          <v-img :src="require('../assets/C.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('D')">
          <v-img :src="require('../assets/D.png')" max-width="48"></v-img>
        </v-btn>
      </v-row>
      <v-row justify="center">
        <v-btn color="success" fab dark @click="changeText('E')">
          <v-img :src="require('../assets/E.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('F')">
          <v-img :src="require('../assets/F.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('G')">
          <v-img :src="require('../assets/G.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('H')">
          <v-img :src="require('../assets/H.png')" max-width="48"></v-img>
        </v-btn>
      </v-row>
      <v-row justify="center">
        <v-btn color="success" fab dark @click="changeText('I')">
          <v-img :src="require('../assets/I.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('J')">
          <v-img :src="require('../assets/J.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('K')">
          <v-img :src="require('../assets/K.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('L')">
          <v-img :src="require('../assets/L.png')" max-width="48"></v-img>
        </v-btn>
      </v-row>
      <v-row justify="center">
        <v-btn color="success" fab dark @click="changeText('M')">
          <v-img :src="require('../assets/M.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('N')">
          <v-img :src="require('../assets/N.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('O')">
          <v-img :src="require('../assets/O.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('P')">
          <v-img :src="require('../assets/P.png')" max-width="48"></v-img>
        </v-btn>
      </v-row>
      <v-row justify="center">
        <v-btn color="success" fab dark @click="changeText('Q')">
          <v-img :src="require('../assets/Q.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('R')">
          <v-img :src="require('../assets/R.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('S')">
          <v-img :src="require('../assets/S.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('T')">
          <v-img :src="require('../assets/T.png')" max-width="48"></v-img>
        </v-btn>
      </v-row>
      <v-row justify="center">
        <v-btn color="success" fab dark @click="changeText('U')">
          <v-img :src="require('../assets/U.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('V')">
          <v-img :src="require('../assets/V.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('W')">
          <v-img :src="require('../assets/W.png')" max-width="48"></v-img>
        </v-btn>
        <v-btn color="success" fab dark @click="changeText('X')">
          <v-img :src="require('../assets/X.png')" max-width="48"></v-img>
        </v-btn>
      </v-row>
      <v-row justify="center">
        <v-center>
          <v-btn color="success" fab dark @click="changeText('Y')">
            <v-img :src="require('../assets/Y.png')" max-width="48"></v-img>
          </v-btn>
          <v-btn color="success" fab dark @click="changeText('Z')">
            <v-img :src="require('../assets/Z.png')" max-width="48"></v-img>
          </v-btn>
          <v-btn color="red lighten-1" fab dark @click="clearText()">Clear</v-btn>
        </v-center>
      </v-row>
    </v-col>
    <!-- <div class="my-2">
      <v-btn color="success" fab x-large dark @click="changeText('A')">
        <v-img :src="require('../assets/A.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('B')">
        <v-img :src="require('../assets/B.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('C')">
        <v-img :src="require('../assets/C.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('D')">
        <v-img :src="require('../assets/D.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('E')">
        <v-img :src="require('../assets/E.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('F')">
        <v-img :src="require('../assets/F.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('G')">
        <v-img :src="require('../assets/G.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('H')">
        <v-img :src="require('../assets/H.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('I')">
        <v-img :src="require('../assets/I.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('J')">
        <v-img :src="require('../assets/J.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('K')">
        <v-img :src="require('../assets/K.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('L')">
        <v-img :src="require('../assets/L.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('M')">
        <v-img :src="require('../assets/M.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('N')">
        <v-img :src="require('../assets/N.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('O')">
        <v-img :src="require('../assets/O.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('P')">
        <v-img :src="require('../assets/P.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('Q')">
        <v-img :src="require('../assets/Q.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('R')">
        <v-img :src="require('../assets/R.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('S')">
        <v-img :src="require('../assets/S.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('T')">
        <v-img :src="require('../assets/T.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('U')">
        <v-img :src="require('../assets/U.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('V')">
        <v-img :src="require('../assets/V.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('W')">
        <v-img :src="require('../assets/W.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('X')">
        <v-img :src="require('../assets/X.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('Y')">
        <v-img :src="require('../assets/Y.png')" max-width="60"></v-img>
      </v-btn>
      <v-btn color="success" fab x-large dark @click="changeText('Z')">
        <v-img :src="require('../assets/Z.png')" max-width="60"></v-img>
      </v-btn>
    </div>-->
  </v-container>
</template>

<script>
export default {
  name: "TextArea",
  data: () => ({
      
  }),
  methods: {
    changeText(val) {
      document.getElementById("Text").value += `${val}`;
    },
    clearText() {
      let current_value = document.getElementById("Text").value;
      current_value = current_value.slice(0, current_value.length - 1);
      document.getElementById("Text").value = current_value;
    },
    copyToClipboard() {
      var copyText = document.getElementById("Text");
      copyText.select();
      copyText.setSelectionRange(0, 99999);

      document.execCommand("copy");

      alert("Copied the text: " + copyText.value);
    }
  },
  mounted() {
    document.getElementById("Text").disabled = true;
  }
};
</script>

<style>
.mirror {
  -webkit-transform: scaleX(-1);
  transform: scaleX(-1);
}
</style>
<template>
  <div>
    <index-navbar />
    <section
      class="header relative pt-16 items-center flex h-screen max-h-860-px"
    >
      <div class="container mx-auto items-center flex flex-wrap">
        <div class="w-full md:w-8/12 lg:w-6/12 xl:w-6/12 px-4">
          <div class="pt-32 sm:pt-0">
            <h3 class="font-semibold text-4xl text-blueGray-600">
              Profil Desa
            </h3>
            <h2 class="font-semibold text-4xl text-blueGray-600">
              Desa Ciasihan
            </h2>
            <p class="mt-4 text-lg leading-relaxed text-blueGray-500">
              Kecamatan Pamijahan, Kabupaten Bogor
            </p>
            <div class="mt-5">
              <iframe class="rounded-md" width="500"  height="280" src="https://www.youtube.com/embed/qTlLhaxq8S8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
            </iframe>
            </div>
          </div>
        </div>
      </div>

      <img
        class="absolute top-0 b-auto right-0 pt-16 sm:w-6/12 -mt-48 sm:mt-0 w-10/12 max-h-860-px"
        :src="patternVue"
        alt="..."
      />
    </section>

    <section class="mt-48 md:mt-40 pb-40 relative bg-blueGray-100">
      <div
        class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20"
        style="transform: translateZ(0);"
      >
        <svg
          class="absolute bottom-0 overflow-hidden"
          xmlns="http://www.w3.org/2000/svg"
          preserveAspectRatio="none"
          version="1.1"
          viewBox="0 0 2560 100"
          x="0"
          y="0"
        >
          <polygon
            class="text-blueGray-100 fill-current"
            points="2560 0 2560 100 0 100"
          ></polygon>
        </svg>
      </div>
      <div class="container mx-auto">
        <div class="flex flex-wrap items-center">
          <div
            class="w-10/12 md:w-6/12 lg:w-4/12 px-12 md:px-4 mr-auto ml-auto -mt-32"
          >
            <div
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-emerald-500"
            >
              <img
                alt="..."
                :src="desaWisata"
                class="w-full align-middle rounded-t-lg"
              />
              <blockquote class="relative p-8 mb-4">
                <svg
                  preserveAspectRatio="none"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 583 95"
                  class="absolute left-0 w-full block h-95-px -top-94-px"
                >
                  <polygon
                    points="-30,95 583,95 583,65"
                    class="text-emerald-500 fill-current"
                  ></polygon>
                </svg>
                <h4 class="text-xl font-bold text-white">
                  Transformasi Desa Wisata menjadi desa Mandiri
                </h4>
                <p class="text-md font-light mt-2 text-white">
                  Setelah disahkan menjadi Desa Wisata pada masa jabatan Kepala Desa Bapak PANDI oleh Dinas Pariwisata Kabupaten Bogor tahun 2013,  maka Desa Ciasihan mulai berbenah sebagai daerah tujuan untuk belajar sekaligus berekreasi menikmati udara pegunungan yang sejuk dan kesederhanaan kehidupan masyarakat kampung dengan segala aktifitasnya. <br>
                  Dan diawal tahun 2023 pada masa jabatan Kepala Desa Ibu. LILIH N, S.I.P desa Ciasihan yang awalnya Desa Ciasihan yang berstatus Desa Berkembang kini resmi mejadi Desa Mandiri.
                </p>
              </blockquote>
            </div>
          </div>

          <div class="w-full md:w-6/12 px-4">
            <div class="flex flex-wrap">
              <div class="w-full md:w-12/12 px-4 mb-4" >
                <h2 class="font-semibold text-4xl text-blueGray-600">Visi Desa Ciasihan :</h2>
              </div>
              <div class="w-full md:w-12/12 px-4">
                <p class="text-xl mb-1 font-semibold">
                  “ Mewujudkan Tata Kelola Pemerintahan Yang Baik dan Transparan Guna Tercapainya Kehidupan Masyarakat Desa Ciasihan Yang Religius, Maju, Aman dan Bermartabat”
                </p>
              </div>
              <div class="w-full md:w-12/12 px-4 mt-4">
                <h2 class="font-semibold text-3xl text-blueGray-600">Misi Desa Ciasihan : </h2>
              </div>
              <div class="w-full md:w-6/12 px-4">
                <div class="relative flex flex-col mt-4">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-sitemap"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Pemerintahan
                    </h6>
                    <p class="mb-4 text-blueGray-500">
                      Menyelenggarakan pemerintahan yang transparan, akuntabilitas, partisipatif dan responsif.
                    </p>
                  </div>
                </div>
                <div class="relative flex flex-col min-w-0">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-drafting-compass"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Pertanian
                    </h6>
                    <p class="mb-4 text-blueGray-500">
                      Menumbuhkembangkan potensi pertanian dan pariwisata secara optimal dan lestari.
                    </p>
                  </div>
                </div>
              </div>
              <div class="w-full md:w-6/12 px-4">
                <div class="relative flex flex-col min-w-0 mt-4">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-newspaper"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">Informasi</h6>
                    <p class="mb-4 text-blueGray-500">
                      Melakukan informasi pelayanan masyarakat menuju tata pemerintahan yang lebih baik.
                    </p>
                  </div>
                </div>
                <div class="relative flex flex-col min-w-0">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-file-alt"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Kualitas
                    </h6>
                    <p class="mb-4 text-blueGray-500">
                      Meningkatkan kualitas Sumber Daya Alam (SDA) dan Sumber Daya Manusia (SDM).
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="container mx-auto overflow-hidden pb-20">

        <div class="flex flex-wrap items-center pt-32">
          <div class="w-full md:w-6/12 px-4 mr-auto ml-auto mt-32">
            <div class="justify-center flex flex-wrap relative">
              <h2 class="font-semibold text-4xl text-blueGray-600 mb-4 mt-3 underline">URUTAN PEJABAT KEPALA DESA</h2>
              <div class="my-4 w-full lg:w-6/12 px-4">
                <a
                  href="#"
                >
                  <div class="bg-red-600 shadow-lg rounded-lg text-center p-8">
                    <img
                      alt="..."
                      class="shadow-md rounded-full max-w-full w-15 mx-auto p-2 bg-white"
                      :src="unang"
                    />
                    <p class="text-lg text-white font-semibold underline">
                      Unang Sumantri
                    </p>
                    <ul class="text-white font-semibold">
                      <li>Masa Jabatan : 8 Tahun</li>
                      <li>Periode Tahun : 1982 - 1990</li>
                    </ul>
                  </div>
                </a>
                <a
                  href="#"
                >
                  <div
                    class="bg-lightBlue-500 shadow-lg rounded-lg text-center p-8 mt-8"
                  >
                    <img
                      alt="..."
                      class="shadow-md rounded-full max-w-full w-15 mx-auto p-2 bg-white"
                      :src="dedi"
                    />
                    <p class="text-lg text-white mt-4 font-semibold underline">
                      Dedi Supriadi
                    </p>
                    <ul class="text-white font-semibold">
                      <li>Masa Jabatan : 8 Tahun</li>
                      <li>Periode Tahun : 1990 - 1998</li>
                    </ul>
                  </div>
                </a>
                <a
                  href="#"
                >
                  <div
                    class="bg-blueGray-700 shadow-lg rounded-lg text-center p-8 mt-8"
                  >
                    <img
                      alt="..."
                      class="shadow-md rounded-full max-w-full w-15 mx-auto p-2 bg-white"
                      :src="eman"
                    />
                    <p class="text-lg text-white mt-4 font-semibold underline">
                      E. Sulaeman Rasyid
                    </p>
                    <ul class="text-white font-semibold">
                      <li>Masa Jabatan : 8 Tahun</li>
                      <li>Periode Tahun : 1998 - 2006</li>
                    </ul>
                  </div>
                </a>
              </div>
              <div class="my-4 w-full lg:w-6/12 px-4 lg:mt-16">
                <a
                  href="#"
                >
                  <div
                    class="bg-yellow-500 shadow-lg rounded-lg text-center p-8"
                  >
                    <img
                      alt="..."
                      class="shadow-md rounded-full max-w-full w-15 mx-auto p-2 bg-white"
                      :src="dedi"
                    />
                    <p class="text-lg text-white mt-4 font-semibold underline">
                      Dedi Supriadi
                    </p>
                    <ul class="text-white font-semibold">
                      <li>Masa Jabatan : 6 Tahun</li>
                      <li>Periode Tahun : 2006 - 2012</li>
                    </ul>
                  </div>
                </a>
                <a
                  href="#"
                >
                  <div
                    class="bg-red-700 shadow-lg rounded-lg text-center p-8 mt-8"
                  >
                    <img
                      alt="..."
                      class="shadow-md rounded-full max-w-full w-15 mx-auto p-2 bg-white"
                      :src="pandi"
                    />
                    <p class="text-lg text-white mt-4 font-semibold underline">
                      Pandi
                    </p>
                    <ul class="text-white font-semibold">
                      <li>Masa Jabatan : 6 Tahun</li>
                      <li>Periode Tahun : 2013 - 2019</li>
                    </ul>
                  </div>
                </a>
                <a
                  href="#"
                >
                  <div
                    class="bg-emerald-500 shadow-lg rounded-lg text-center p-8 mt-8"
                  >
                    <img
                      alt="..."
                      class="shadow-md rounded-full max-w-full w-15 mx-auto p-2 bg-white"
                      :src="lilih"
                    />
                    <p class="text-lg text-white mt-4 font-semibold underline">
                      Lilih N, S.I.P
                    </p>
                    <ul class="text-white font-semibold">
                      <li>Masa Jabatan : 6 Tahun</li>
                      <li>Periode Tahun : 2019 - 2025</li>
                    </ul>
                  </div>
                </a>
              </div>
            </div>
          </div>

          <div class="w-full md:w-4/12 px-12 md:px-4 ml-auto mr-auto mt-48">
            <h3 class="text-3xl mb-2 font-semibold leading-normal">
              Sejarah Singkat Desa Ciasihan 
            </h3>
            <p
              class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-600"
            >
            Desa Ciasihan merupakan salah satu desa yang terletak di Kecamatan Pamijahan Kabupaten Bogor Provinsi Jawa Barat. Desa Ciasihan adalah desa hasil pemekaran yang dahulunya adalah Desa Ciasmara yang berada diwilayah kecamatan cibungbulang, dan sekitar tahun 1978 ada pemekaran wilayah kecamatan yang dahulunya desa ciasmara kecamatan Cibungbulang menjadi desa Ciasmara kecamatan Pamijahan.
            </p>
            <p
              class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-600"
            >
            Dikarenakan wilayah desa ciasmara cukup luas, maka sekitar tahun 1982 yang dahulu satu desa yang bernama Desa Ciasmara terjadi pemecahan atau pemekaran wilayah oleh pemerintah daerah menjadi tiga desa yaitu desa Ciasihan, Ciasmara dan Purwabakti. 
            Desa Ciasihan sendiri letak biografisnya diapit oleh dua sungai terkenal yaitu sungai Cikuluwung dan sungai Ciasmara.<br>
            Dari awal terbentuknya desa ciasihan dari tahun 1982 sampai dengan tahun 2023 Desa Ciasihan sudah dipimpin oleh Lima orang kepala desa.

            </p>
          </div>
        </div>
      </div>

      <div class="container mx-auto px-4 pb-32 pt-48">
        <div class="items-center flex flex-wrap">
          <div class="w-full md:w-5/12 ml-auto px-12 md:px-4">
            <div class="md:pr-12">
              <h3 class="text-3xl font-semibold">
                Kantor Kepala Desa Ciasihan
              </h3>
              <p class="mt-4 text-lg leading-relaxed text-blueGray-500">
                Beralamat di Jl. KH.M. Parta Ciasihan, Kec. Pamijahan, Kabupaten Bogor, Jawa Barat 16810
              </p>
            </div>
          </div>

          <div class="w-full md:w-6/12 mr-auto px-4 pt-24 md:pt-0">
            <img
              alt="..."
              class="max-w-full rounded-lg shadow-xl"
              style="
                transform: scale(1) perspective(1040px) rotateY(-11deg)
                  rotateX(2deg) rotate(2deg);
              "
              :src="documentation"
            />
          </div>
        </div>
      </div>

      <div class="justify-center text-center flex flex-wrap mt-24">
        <div class="w-full md:w-6/12 px-12 md:px-4">
          <h2 class="font-semibold text-4xl">Destinasi Wisata Desa Ciasihan</h2>
          <p class="text-lg leading-relaxed mt-4 mb-4 text-blueGray-500">
            Desa Ciasihan memiliki banyak destinasi wisata, terutama wisata alam dan pegunungan.
            Mulai dari wisata air, curug, pegunungan, persawahaan, perkemahan dan masih banyak yang lain.
          </p>
        </div>
      </div>
    </section>

    <section class="block relative z-1 bg-blueGray-600">
      <div class="container mx-auto">
        <div class="justify-center flex flex-wrap">
          <div class="w-full lg:w-12/12 px-4 -mt-24">
            <div class="flex flex-wrap">
              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Curug Walet
                </h5>
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="login"
                    />
                  </div>
              </div>

              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Puncak Menir
                </h5>
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="profile"
                    />
                  </div>
              </div>

              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Cikuluwung Rever  
                </h5>
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="landing"
                    />
                  </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="py-20 bg-blueGray-600 overflow-hidden">
      <div class="container mx-auto pb-64">

      </div>
    </section>

    <section class="pb-16 bg-blueGray-200 relative pt-32">
      <div
        class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20"
        style="transform: translateZ(0);"
      >
        <svg
          class="absolute bottom-0 overflow-hidden"
          xmlns="http://www.w3.org/2000/svg"
          preserveAspectRatio="none"
          version="1.1"
          viewBox="0 0 2560 100"
          x="0"
          y="0"
        >
          <polygon
            class="text-blueGray-200 fill-current"
            points="2560 0 2560 100 0 100"
          ></polygon>
        </svg>
      </div>

      <div class="container mx-auto">
        <div
          class="flex flex-wrap justify-center bg-white shadow-xl rounded-lg -mt-64 py-16 px-12 relative z-10"
        >
          <div class="w-full text-center lg:w-8/12">
            <p class="text-4xl text-center">
              <span role="img" aria-label="love">
                😍
              </span>
            </p>
            <h3 class="font-semibold text-3xl">
              Terimakasih telah mengunjungi kami.
            </h3>
            <p class="text-blueGray-500 text-lg leading-relaxed mt-4 mb-4">
              Ayo kunjungi Desa Ciasihan dengan wisata alam yang banyak, kita bisa merasakan indahnya alam sembari berwisata.
            </p>
            <div class="text-center mt-16"></div>
          </div>
        </div>
      </div>
    </section>
    <footer-component />
  </div>
</template>
<script>
import IndexNavbar from "@/components/Navbars/IndexNavbar.vue";
import FooterComponent from "@/components/Footers/Footer.vue";

import unang from "@/assets/img/user.png";
import dedi from "@/assets/img/dedi.png";
import pandi from "@/assets/img/pandi.png";
import eman from "@/assets/img/eman.png";
import lilih from "@/assets/img/lilih.png";
import desaWisata from "@/assets/img/desawisata.png";
import patternVue from "@/assets/img/ciasihan.png";
import documentation from "@/assets/img/balaiCiasihan.jpg";
import login from "@/assets/img/curugwalet.jpeg";
import profile from "@/assets/img/menir.jpeg";
import landing from "@/assets/img/cikuluwung.jpg";

export default {
  data() {
    return {
      unang,
      dedi,
      pandi,
      eman,
      lilih,
      desaWisata,
      patternVue,
      documentation,
      login,
      profile,
      landing,
    };
  },
  components: {
    IndexNavbar,
    FooterComponent,
  },
};
</script>

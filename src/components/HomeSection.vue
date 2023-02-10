<template>
  <q-section id="about">
    <div class="flex justify-center text-center column">
      <div class="section-title relative-position text-center q-my-sm">
        <span class="relative-position fw-bolder fs-1 text-light"
          >About Me</span
        >
        <h2
          class="relative-position fw-bolder text-secondary q-mt-none fs-2"
          style="z-index: 2"
        >
          About Me
        </h2>
      </div>
      <q-card class="q-pa-md q-ma-xl">
        <div class="row">
          <div class="col">
            <div class="row item-center">
              <div>
                <q-icon
                  name="fa-solid fa-chevron-right"
                  color="secondary"
                  size="1em"
                  class="q-pr-md"
                />
              </div>
              <strong>Name:</strong>
              <p>&nbsp;&nbsp;Leclercq Vincent</p>
            </div>
            <div class="row">
              <div>
                <q-icon
                  name="fa-solid fa-chevron-right"
                  color="secondary"
                  size="1em"
                  class="q-pr-md"
                />
              </div>
              <strong>Website:</strong>
              <p>&nbsp;&nbsp;www.leclercqvincent.com</p>
            </div>
            <div class="row">
              <div>
                <q-icon
                  name="fa-solid fa-chevron-right"
                  color="secondary"
                  size="1em"
                  class="q-pr-md"
                />
              </div>
              <strong>Home address:</strong>
              <p>&nbsp;&nbsp; Champigny, 51370, France</p>
            </div>
          </div>
          <div class="col">
            <div class="row">
              <div>
                <q-icon
                  name="fa-solid fa-chevron-right"
                  color="secondary"
                  size="1em"
                  class="q-pr-md"
                />
              </div>
              <strong>Age:</strong>
              <p>&nbsp;&nbsp; 20 ans</p>
            </div>
            <div class="row">
              <div>
                <q-icon
                  name="fa-solid fa-chevron-right"
                  color="secondary"
                  size="1em"
                  class="q-pr-md"
                />
              </div>
              <strong>Diploma:</strong>
              <p>
                &nbsp;&nbsp; BAC + 3, Cycle préparatoire d'école d'ingénieur
              </p>
            </div>
            <div class="row">
              <div>
                <q-icon
                  name="fa-solid fa-chevron-right"
                  color="secondary"
                  size="1em"
                  class="q-pr-md"
                />
              </div>
              <strong>Email:</strong>
              <p>&nbsp;&nbsp;LeclercqVincent@outlook.com</p>
            </div>
          </div>
        </div>
        <div class="row">
          <p>
            I am a student in engineering school. I like computer science and
            new technologies but also sports, reading and video games. For the
            moment, I diversify my skills and experiences within my school and
            professionally. I appreciate teamwork. Since my beginnings in
            computer science, I am fascinated by artificial intelligence and
            augmented and virtual reality.
          </p>
          <p>
            I have seen several programming languages including C and C++ with
            object-oriented programming. I also discovered the different web
            languages around projects (Html, CSS, php, javascript) as well as
            SQL.
          </p>
        </div>
      </q-card>
    </div>
  </q-section>
</template>

<script>
export default {
  name: 'HomeSection',
  setup() {
    return {};
  },
};
</script>

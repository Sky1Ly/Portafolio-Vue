<template>
  <div class="d-flex flex-column min-vh-100">
    <header class="px-4 py-3 d-flex align-items-center">
      <a href="#" class="d-flex align-items-center justify-content-center">
        <BriefcaseIcon class="h-6 w-6" />
        <span class="sr-only">My Portfolio</span>
      </a>
      <nav class="ml-auto d-flex gap-3">
        <a href="#" class="text-sm font-medium text-decoration-none">
          About
        </a>
        <a href="#" class="text-sm font-medium text-decoration-none">
          Projects
        </a>
        <a href="#" class="text-sm font-medium text-decoration-none">
          Contact
        </a>
      </nav>
    </header>
    <main class="flex-grow-1">
      <section id="hero" class="w-100 py-4 py-md-5">
        <div class="container px-4">
          <div class="row gap-3 gap-lg-4">
            <div class="col-lg-8 d-flex flex-column justify-content-center space-y-4">
              <div class="space-y-2">
                <h1 class="display-4 font-bold">Hi, I'm John Doe</h1>
                <p class="text-muted">
                  I'm a full-stack developer with a passion for building beautiful and functional web applications.
                </p>
              </div>
              <div class="d-flex flex-column flex-md-row gap-2">
                <a
                  href="#"
                  class="btn btn-primary"
                >
                  View My Work
                </a>
                <a
                  href="#"
                  class="btn btn-outline-secondary"
                >
                  Get in Touch
                </a>
              </div>
            </div>
            <div class="col-lg-4">
              <img
                src="../src/assets/4710019.jpg"
                class="img-fluid rounded-xl w-50"
                alt="Hero"
              />
            </div>
          </div>
        </div>
      </section>
      <section id="projects" class="w-100 py-4 py-md-5 bg-light">
        <div class="container px-4">
          <div class="text-center mb-4">
            <span class="badge bg-secondary text-white">Featured Projects</span>
            <h2 class="h1 font-bold">Check out my work</h2>
            <p class="text-muted">
              I've worked on a variety of projects, from web applications to mobile apps. Here are some of my featured projects.
            </p>
          </div>
          <div class="row gap-3 gap-lg-4">
            <div class="col-lg-6">
              <img
                src="../src/assets/4710019.jpg"
                class="img-fluid rounded-xl w-50"
                alt="Project 1"
              />
            </div>
            <div class="col-lg-6 d-flex flex-column justify-content-center">
              <h3 class="h4 font-bold">Project 1</h3>
              <p class="text-muted">
                A web application that helps users manage their tasks and projects. Built with React, Node.js, and MongoDB.
              </p>
              <div class="d-flex flex-column flex-md-row gap-2">
                <a
                  href="#"
                  class="btn btn-primary"
                >
                  View Project
                </a>
                <a
                  href="#"
                  class="btn btn-outline-secondary"
                >
                  GitHub
                </a>
              </div>
            </div>
          </div>
          <div class="row gap-3 gap-lg-4 mt-4">
            <div class="col-lg-6">
              <img
                src="../src/assets/4710019.jpg"
                class="img-fluid rounded-xl w-50"
                alt="Project 2"
              />
            </div>
            <div class="col-lg-6 d-flex flex-column justify-content-center">
              <h3 class="h4 font-bold">Project 2</h3>
              <p class="text-muted">
                A mobile app that helps users track their fitness goals. Built with React Native and Firebase.
              </p>
              <div class="d-flex flex-column flex-md-row gap-2">
                <a
                  href="#"
                  class="btn btn-primary"
                >
                  View Project
                </a>
                <a
                  href="#"
                  class="btn btn-outline-secondary"
                >
                  GitHub
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section id="contact" class="w-100 py-4 py-md-5 border-top">
        <div class="container px-4">
          <div class="row gap-4">
            <div class="col-md-6">
              <span class="badge bg-secondary text-white">Get in Touch</span>
              <h2 class="h1 font-bold">Let's work together</h2>
              <p class="text-muted">
                I'm always excited to work on new projects. If you have an idea or just want to chat, feel free to reach out.
              </p>
            </div>
            <div class="col-md-6">
              <form class="d-flex flex-column gap-3">
                <input type="text" class="form-control" placeholder="Name" />
                <input type="email" class="form-control" placeholder="Email" />
                <textarea class="form-control" placeholder="Message"></textarea>
                <button type="submit" class="btn btn-primary">
                  Send Message
                </button>
              </form>
            </div>
          </div>
        </div>
      </section>
    </main>
    <footer class="d-flex flex-column flex-md-row py-3 w-100 border-top">
      <p class="text-xs text-muted">&copy; 2024 John Doe. All rights reserved.</p>
      <nav class="ms-auto d-flex gap-3">
        <a href="#" class="text-xs text-decoration-none">
          Terms of Service
        </a>
        <a href="#" class="text-xs text-decoration-none">
          Privacy
        </a>
      </nav>
    </footer>
  </div>
</template>

<style scoped>
.min-vh-100 {
  min-height: 100vh;
}
</style>

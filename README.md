export default function PortfolioWebsite() {
  return (
    <div className="min-h-screen bg-black text-white font-sans">

      {/* Hero Section */}
      <section className="flex flex-col items-center justify-center text-center min-h-screen px-6 bg-gradient-to-b from-black via-gray-900 to-black">
        <h1 className="text-5xl md:text-7xl font-bold mb-4">
          Navdeep Kaur
        </h1>

        <p className="text-xl md:text-2xl text-gray-300 mb-6">
          B.Tech Student • NCC Cadet • Future Developer
        </p>

        <div className="flex gap-4 flex-wrap justify-center">
          <a
            href="#about"
            className="bg-white text-black px-6 py-3 rounded-2xl font-semibold hover:scale-105 transition"
          >
            About Me
          </a>

          <a
            href="#contact"
            className="border border-white px-6 py-3 rounded-2xl hover:bg-white hover:text-black transition"
          >
            Contact
          </a>
        </div>
      </section>

      {/* About */}
      <section id="about" className="max-w-5xl mx-auto px-6 py-20">
        <h2 className="text-4xl font-bold mb-8">About Me</h2>

        <div className="bg-gray-900 rounded-3xl p-8 shadow-2xl">
          <p className="text-lg text-gray-300 leading-8">
            Hello! My name is Navdeep Kaur. I am a B.Tech student from Punjab.
            I am interested in coding, technology, NCC activities, and learning
            new skills.
          </p>
        </div>
      </section>

      {/* Skills */}
      <section className="max-w-5xl mx-auto px-6 py-20">
        <h2 className="text-4xl font-bold mb-10">Skills</h2>

        <div className="grid grid-cols-2 md:grid-cols-4 gap-6">
          {[
            "HTML",
            "CSS",
            "JavaScript",
            "C Programming",
            "Python",
            "Communication",
            "Leadership",
            "Problem Solving",
          ].map((skill) => (
            <div
              key={skill}
              className="bg-gray-900 rounded-2xl p-6 text-center hover:scale-105 transition shadow-lg"
            >
              {skill}
            </div>
          ))}
        </div>
      </section>

      {/* Projects */}
      <section className="max-w-5xl mx-auto px-6 py-20">
        <h2 className="text-4xl font-bold mb-10">Projects</h2>

        <div className="grid md:grid-cols-2 gap-8">
          <div className="bg-gray-900 rounded-3xl p-8 shadow-xl">
            <h3 className="text-2xl font-semibold mb-4">
              Portfolio Website
            </h3>

            <p className="text-gray-300 leading-7">
              A modern personal portfolio website made using React and Tailwind CSS.
            </p>
          </div>

          <div className="bg-gray-900 rounded-3xl p-8 shadow-xl">
            <h3 className="text-2xl font-semibold mb-4">
              Student Projects
            </h3>

            <p className="text-gray-300 leading-7">
              Academic coding projects related to programming and web development.
            </p>
          </div>
        </div>
      </section>

      {/* NCC */}
      <section className="max-w-5xl mx-auto px-6 py-20">
        <h2 className="text-4xl font-bold mb-10">NCC</h2>

        <div className="bg-gray-900 rounded-3xl p-8 shadow-xl">
          <p className="text-lg text-gray-300 leading-8">
            Proud NCC cadet with discipline, leadership, teamwork, and dedication.
          </p>
        </div>
      </section>

      {/* Contact */}
      <section id="contact" className="max-w-5xl mx-auto px-6 py-20">
        <h2 className="text-4xl font-bold mb-10">Contact</h2>

        <div className="bg-gray-900 rounded-3xl p-8 shadow-xl space-y-4">
          <p className="text-lg text-gray-300">
            📧 Email: yourmail@gmail.com
          </p>

          <p className="text-lg text-gray-300">
            📱 Instagram: @yourusername
          </p>

          <p className="text-lg text-gray-300">
            📍 Punjab, India
          </p>
        </div>
      </section>

      {/* Footer */}
      <footer className="text-center py-8 border-t border-gray-800 text-gray-500">
        © 2026 Navdeep Kaur. All rights reserved.
      </footer>

    </div>
  );
}

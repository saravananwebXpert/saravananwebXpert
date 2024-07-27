<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>SaravananwebXpert</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/react/umd/react.production.min.js"></script>
    <script src="https://unpkg.com/react-dom/umd/react-dom.production.min.js"></script>
    <script src="https://unpkg.com/babel-standalone@6.15.0/babel.min.js"></script>

    <style>
      .languages a {
        padding: 2px;
      }
    </style>
  </head>
  <body>
    <div id="root"></div>
    <script type="text/babel">
      const App = () => {
        return (
          <div className="bg-gray-100 p-5">
            <div className="max-w-2xl mx-auto p-5 bg-white rounded-lg shadow-md">
              <h1 className="text-center text-2xl text-gray-800">
                Hi 👋, I'm Saravanan
              </h1>
              <h3 className="text-center text-xl text-gray-700">
                A passionate React Developer from Chennai
              </h3>
              <div className="text-left mb-5">
                <img
                  src="https://komarev.com/ghpvc/?username=saravananwebxpert&label=Profile%20views&color=0e75b6&style=flat"
                  alt="Profile views"
                />
                <p>
                  - 🔭 I’m currently working in{" "}
                  <a
                    href="https://www.solverminds.com/"
                    className="text-blue-500 underline"
                  >
                    Solverminds
                  </a>{" "}
                  on React Project
                </p>
                <p>
                  - 🌱 I’m currently Upskilling{" "}
                  <strong>Full Stack Development & System Design</strong> in{" "}
                  <a
                    href="https://www.scaler.com/"
                    className="text-blue-500 underline"
                  >
                    Scaler
                  </a>
                </p>
                <p>
                  - 💬 Ask me about <strong>React.js, Node.js, Redux</strong>
                </p>
                <p>
                  - ⚡ Fun fact:{" "}
                  <strong>I am a very silent and funny person!</strong>
                </p>
              </div>

              <h3 className="text-center text-lg mt-5">Connect with me:</h3>
              <p className="text-center">
                <a
                  href="https://www.linkedin.com/in/saravanan896"
                  target="_blank"
                  rel="noopener noreferrer"
                >
                  <img
                    src="https://img.shields.io/badge/LinkedIn-0e75b6?style=for-the-badge&logo=linkedin&logoColor=white"
                    alt="LinkedIn"
                  />
                </a>
              </p>

              <h3 className="mt-5">🛠️ Known Languages and Tools:</h3>
              <div className="border border-black flex flex-wrap">
                <div className="border border-black w-full p-3">
                  <h4 className="flex justify-center items-center underline">
                    Frontend
                  </h4>
                  <div className="flex languages flex-wrap justify-center">
                    <a
                      href="https://www.w3.org/html/"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"
                        alt="HTML5"
                      />
                    </a>
                    <a
                      href="https://www.w3schools.com/css/"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"
                        alt="CSS3"
                      />
                    </a>
                    <a
                      href="https://getbootstrap.com"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-Bootstrap-563D7C?style=flat-square&logo=bootstrap&logoColor=white"
                        alt="Bootstrap"
                      />
                    </a>
                    <a
                      href="https://sass-lang.com"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-Sass-CC6699?style=flat-square&logo=sass&logoColor=white"
                        alt="Sass"
                      />
                    </a>
                    <a
                      href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"
                        alt="JavaScript"
                      />
                    </a>
                    <a
                      href="https://www.typescriptlang.org/"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white"
                        alt="TypeScript"
                      />
                    </a>
                    <a
                      href="https://reactjs.org/"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black"
                        alt="React"
                      />
                    </a>
                    <a
                      href="https://redux.js.org"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-Redux-764ABC?style=flat-square&logo=redux&logoColor=white"
                        alt="Redux"
                      />
                    </a>
                  </div>
                </div>

                <div className="border border-black w-full p-3">
                  <h4 className="flex justify-center items-center underline">
                    Backend
                  </h4>
                  <div className=" languages flex flex-wrap justify-center">
                    <a
                      href="https://nodejs.org"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white"
                        alt="Node.js"
                      />
                    </a>
                    <a
                      href="https://expressjs.com"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white"
                        alt="Express"
                      />
                    </a>
                    <a
                      href="https://nestjs.com/"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"
                        alt="NestJS"
                      />
                    </a>
                    <a href="https://redis.io" target="_blank" rel="noreferrer">
                      <img
                        src="https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white"
                        alt="Redis"
                      />
                    </a>
                    <a
                      href="https://www.java.com"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white"
                        alt="Java"
                      />
                    </a>
                    <a
                      href="https://www.mongodb.com/"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"
                        alt="MongoDB"
                      />
                    </a>
                    <a
                      href="https://www.postgresql.org"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"
                        alt="PostgreSQL"
                      />
                    </a>
                    <a
                      href="https://www.python.org"
                      target="_blank"
                      rel="noreferrer"
                    >
                      <img
                        src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white"
                        alt="Python"
                      />
                    </a>
                  </div>
                </div>
              </div>

              <hr className="my-5" />
              <div class="flex items-center justify-center pb-4">
                <img
                  src="https://github-readme-stats.vercel.app/api/top-langs?username=saravananwebxpert&show_icons=true&locale=en&layout=compact"
                  alt="Top languages"
                  className="w-[50%]  h-auto"
                />
              </div>

              <div class=" flex items-center">
                <img
                  src="https://github-readme-stats.vercel.app/api?username=saravananwebxpert&show_icons=true&locale=en"
                  alt="GitHub stats"
                  className="w-[300px] h-auto p-2"
                />
                <img
                  src="https://github-readme-streak-stats.herokuapp.com/?user=saravananwebxpert&"
                  alt="GitHub streak"
                  className="w-[300px] h-auto"
                />
              </div>
            </div>
          </div>
        );
      };

      ReactDOM.render(<App />, document.getElementById("root"));
    </script>
  </body>
</html>

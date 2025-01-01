import { checkReversal } from "../../src/util";

const render = (reversal, color, height) => {
  reversal = checkReversal(reversal);
  const width = 854;

  const PATHS = [
    `M52.8,-67C68,-61.6,79.7,-45.6,82.5,-28.7C85.4,-11.8,79.5,6,71.4,20.8C63.2,35.5,53,47.1,40.7,53.3C28.5,59.4,14.2,60,-2.1,63C-18.5,65.9,-37,71.2,-52.3,66C-67.6,60.9,-79.7,45.4,-81.5,29C-83.2,12.7,-74.6,-4.4,-68.7,-22.2C-62.8,-40.1,-59.5,-58.7,-48.4,-65.4C-37.4,-72.2,-18.7,-67.1,0,-67.1C18.8,-67.2,37.6,-72.4,52.8,-67Z`,
    `M42.3,-55.2C55.2,-48.7,66.6,-37,69.3,-23.7C72,-10.4,66,4.6,58.3,16.1C50.6,27.6,41.2,35.6,31.1,43.9C21.1,52.1,10.6,60.6,-1.3,62.5C-13.2,64.3,-26.4,59.4,-37.6,51.5C-48.8,43.6,-57.9,32.7,-61,20.5C-64.1,8.3,-61.1,-5.3,-57.9,-19.9C-54.7,-34.6,-51.3,-50.3,-41.6,-57.8C-32,-65.3,-16,-64.7,-0.7,-63.7C14.6,-62.8,29.3,-61.6,42.3,-55.2Z`,
    `M49.2,-63.6C62.2,-58.3,70.1,-41.8,74.6,-24.9C79.1,-8.1,80.3,9.2,76.5,26.2C72.8,43.2,64.2,59.9,50.7,68.4C37.1,76.9,18.5,77.2,2.3,74.1C-13.9,70.9,-27.9,64.2,-41.2,55.6C-54.6,47.1,-67.4,36.6,-74.5,22.4C-81.7,8.2,-83.2,-9.7,-74.7,-20.8C-66.3,-31.9,-47.9,-36.3,-33.8,-41.2C-19.7,-46.2,-9.8,-51.8,4.1,-57.5C18.1,-63.1,36.2,-68.9,49.2,-63.6Z`,
  ];

  return `
    <g transform="translate(${width / 2}, ${height / 2})">
      <path id="myPath" fill="${color}" d="${PATHS[0]}" ${reversal}>
        <animate attributeName="d" dur="10s" values="
          ${PATHS.join("; ")};
          ${PATHS[0]}"
          repeatCount="indefinite"
        />
      </path>
    </g>`;
};

export default render;


<div align= "center">
   <img src="https://capsule-render.vercel.app/api?type=transparent&color=gradient&height=120&text=Jin's%20Code%20&animation=fadeIn&fontColor=9edb1a&fontSize=60" />
   </div>
   <div style="text-align: left;"> 
   <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;">  </h2>  
   <div style="font-weight: 700; font-size: 15px; text-align: left; color: #282d33;">  </div> 
   </div>
   <div style="text-align: left;">
   <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🛠️ Tech Stacks </h2> <br> 
   <div style="margin: ; text-align: left;" "text-align: left;"> <img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=for-the-badge&logo=Tensorflow&logoColor=white">
         <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
         <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white">
         <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white">
         <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white">
         <br/><img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white">
         <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
         <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white">
         <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=Flask&logoColor=white">
         <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white">
         <br/><img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=Linux&logoColor=white">
         </div>
   </div>
   <div style="text-align: left;">
   <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🧑‍💻 Contact me </h2> <br> 
   <div style="text-align: left;"> <a href=https://jjincoding-helloworld.tistory.com/> <img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=Velog&logoColor=white&link=https://jjincoding-helloworld.tistory.com/"> </a>
        <a href=mailto:uuuj0821@naver.com> <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white&link=mailto:uuuj0821@naver.com"> </a>
         </div>  <br> 
   <div style="text-align: left;">  </div> 
   </div>
   <div style="text-align: left;"> 
   <h2 style="border-bottom: 1px solid #; color: #282d33;"> 🏅 Stats </h2> 
       <div style="text-align: left;"> 
             <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=uuuj0821&layout=compact&hide=javascript,css,scss&langs_count=8"/>
<img src=https://github-readme-stats.vercel.app/api?username=uuuj0821&show_icons=true
         /> 
       </div> 
   </div>

   [![Solved.ac 프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=uuuj0821)](https://solved.ac/uuuj0821)


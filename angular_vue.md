
1 A brief history of  Angular Vs Vue

angular

由谷歌开发的Angular于 2010 年首次发布，使其成为最古老的。它是一个基于 TypeScript 的 JavaScript 框架。2016 年 Angular 2 的发布发生了重大转变（并且从原来的名称 AngularJS 中删除了“JS”）。Angular 2+ 被称为Angular。尽管 AngularJS（版本 1）仍在更新，但我们将重点讨论 Angular。最新的稳定版本是 Angular 11，它于 2020 年 11 月发布

Vue
Vue也称为 Vue.js，是该组中最年轻的成员。它由前 Google 员工 Evan You 于 2014 年开发。在过去三年中，Vue 的受欢迎程度发生了重大变化，尽管它没有得到大公司的支持。当前的稳定版本是 3.0，于 2020 年 9 月发布（此后有一些小的增量版本）。

                Angular	        	Vue
Initial release	2010		        2014
Official site	angular.io		    vuejs.org
Current version	11		            3.0.x
Used by	Google, Facebook	    Alibaba, GitLab

2 Market Usage Statistics – Angular vs. Vue

Angular在GitHub 上拥有 75.5k star、19.7k forks、大约 1444 名贡献者。 
Vue公司 大约为186K start，29.8k forks,大约 399 名贡献者。
https://www.npmtrends.com/angular-vs-react-vs-vue

3 Pros and Cons of Angular and Vue

Angular 的优点
TypeScript 的优势    – JavaScript 的超集提供了重构服务和自动完成功能，在开发企业级应用程序时消除了代码中的错误（静态类型检查）。 
Google 的支持        –长期的 Google 支持以详细的文档和通过改进的开发功能扩展框架的进一步可能性为后盾。 
高性能               –通过分层依赖注入、Ivy 渲染器、AOT 编译器、差异加载和 Angular Universal 支持，为开发人员提供高性能。 
更新建议             –Angular 命令行界面提供依赖项、加载器和插件所需的时时建议。  (https://update.angular.io/)
第三方集成           –第三方集成——该框架允许轻松集成第三方应用程序，为开发进度提供更多的灵活性和工具 ()                  
                      https://angular.schule/blog/2019-02-third-party-libraries-and-widgets

Angular 的缺点
复杂性               —尽管其基于组件的架构，组件的管理和重复性使得前端框架对其开发社区来说变得冗长。 
版本                 —从 AngularJS 迁移到 Angular 对开发人员来说是一个巨大的麻烦，尤其是当框架应用程序很大时。此外，了解每个版本会使学习曲线更陡峭并降低其受欢迎程度。
臃肿学习曲线          —简单和小型应用程序可能会变得臃肿，因为它们需要样板代码、抽象概念和其他捆绑功能。
使用热度              —国内使用热度不及vue

Vue 的优点 
渐进式                –通过在开发组件的过程中逐步将框架引入代码，可以轻松管理 Vue 的迁移或集成，而无需浪费任何开发时间。 
传统                  –Vue 通过使用内置解决方案来创建管理组件和动画的状态支持，不会使编写样板代码变得更加困难。传统方法使使用 Vue 构建应用程序的整个过程更快。 
有效大小              –随着 Vue 的每个新版本的发布，框架变得更轻、更快。Vue 的优化能力允许开发人员更多地关注功能添加而不是调试或代码调整。 
功能扩展              –Vue 提供了一组基于功能的附加 API 特性，允许应用程序中组件逻辑的组合灵活和广泛。因此，应用程序组件可以根据需要变得更具可读性和扩展功能。
面向未来              –Vue 以其强大的生产环境而闻名，因此无需更新或定期检查应用程序是否已修复错误或改进。默认情况下，该框架使更新过程更容易。 

Vue 的缺点 
社区                  –Vue 有一个缺乏语言可理解性的社区。随着 Vue 在中国各地的流行，对 Vue 的大部分讨论都是用中文进行的，这使得英语开发者难以学习和共享资源。 。 
支持                  –Vue 仍然被认为是一个年轻的框架，并且由于它的社区在被大型项目采用时相对较小，解决经验不足的开发人员无法处理大型项目出现的问题。 
灵活性风险             –拥有灵活性和自定义选项总是合理的，但 Vue 提供了太多的灵活性。它通常被认为是一个框架，其中过多的选项使项目过于复杂，从而导致错误和代码违规。 
资源限制               -Vue 的生态虽然广泛，但仍然没有提供与大多数外部工具源和其他框架通常兼容的插件和工具。它还缺乏对大多数可用的支持资源。

4 What about syntax?

Angular 使用 TypeScript（带有注入器和装饰器, Vue 在语法方面更简单。
<div>
  <h2>Hello {{name}}</h2>
</div>
Import {  Component  } from ‘@angular/core’ ;

@Component ({
  selector:  ‘my – app’,
  templateUrl:  ‘src/app/app.component.html’
})

export class AppComponent {
  constructer() {}
  name: string = ‘Angular 2’;
}


<!DOCTYPE html>
<html lang="en">
    <meta>
       <meta charset="UTF-8">
        <title>Hello world example</title>
     </meta> 

<body>

    <div id="hello-world-example">
        <h1>{{ hello world }}</h1>
    </div>

    <script>
       new vue({
           el: "#hello-world-example",
           data()  {
              return  {
                  msg: "Hello World!"
               }
          }
     });
     </script>

  </body>
</html>

https://www.freecodecamp.org/news/angular-vs-vue-which-is-best-for-programming-in-2020/


5 who is winner?

when: 用于创建复杂和大型企业应用程序，在未来构建可扩展的产品时，推荐Angular;团队规模小，时间短，选择 Vue 比较方便；
what: 两个个有千秋的框架
who:  对于刚开始使用前端 JavaScript 框架的人、初创公司和喜欢灵活性的开发人员来说，推荐VUE；对于拥有大型团和已经使用 TypeScript 的开发人员的公司来,推荐
where:大型公司：angular;中小型公司：vue;
how:  Angular:https://angular.cn/;Vue: https://v3.cn.vuejs.org/guide/introduction.html;

6 who use the two frame

Angular
Mixer –视频游戏的实时流媒体平台结合了 Angular 来创建其视频流媒体设施的界面。它还帮助团队实时更新单页应用程序的数据。
Gmail –单页邮件应用程序使用 Angular 作为其动态界面。该站点在前端呈现数据，支持离线访问缓存数据，并结合了多项 SPA 优势。 
PayPal ——在线支付处理网站结合了 Angular 来实现惊人的网站性能并轻松处理用户交易的高峰。它的几次点击授权和结帐页面是在 Angular 的帮助下构建的一些其他功能。 
福布斯——美国杂志的数字版使用 Angular 5 作为其用户界面，它有能力响应美国 7400 万月度用户。 
Weather.com -天气频道为其 UI 合并了 Angular，该 UI 由单独的团队为其单独的目录管理。Angular 允许站点集成多个地图、实时广播和视频流以进行新闻更新。 
Microsoft Office –文档软件通过其 Office 365 API 在在线平台上进行了大胆的迁移。通过使用 Angular，应用程序的单页视图和优秀的 UI 成为可能。

vue
Gitlab - 实现支持现有社区改进其报告、管理、代码管理和分析的复杂功能。GitLab 对 Vue 进行了缓慢迁移，因为它可以简单地创建高级组件而无需付出太多努力
Adobe  - 产品组合：Vue 实现了从旧框架迁移而不会造成数据丢失或复杂化的必要性。在 Vue 的帮助下，Adobe 构建了自定义工具，允许用户通过以下方式开发现代化的网站 Adobe 创意
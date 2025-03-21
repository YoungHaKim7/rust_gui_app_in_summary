# Introduction to Pax(공식 문서 잘 정리됨.)
- https://docs.pax.dev/

# 웹홈페이지 만들기 좋네..User interface engine with an integrated vector design tool, built in Rust 
- https://github.com/paxdotdev/pax

# (Youtube소개영상)Meet Pax | Pax
- https://youtu.be/crI_raloHgo?si=NicCFl1ZbmHEn5NX

# Pax enters Beta: Rust GUIs with an integrated design tool (self.rust)
- submitted 6 months ago by zackaboo

- Hey all!  We are Zack, Warfa, and Sam; after some man-years of building Pax, we're excited finally to enter Beta and to invite anyone to build with Pax for the first time.

- What is Pax?
  - Pax is a tool for building native apps & websites, similar to SwiftUI or Flutter. Pax is driven by a declarative user interface description language that attaches to Rust application logic. Pax itself is built in Rust.

Pax ships with an integrated vector design tool.  This design tool is a bidirectional view into any Pax codebase: open codebase with designer, make visual changes, edit pax-lang or Rust by hand with any code editor, and continue to switch back and forth between visual and written modes. How does this work? 

Unlike most visual builders, Pax Designer has the tools, features, and conventions of a professional vector design tool (like Figma, Illustrator, or Flash.) This foundational goal required careful design of every aspect of Pax, from the grammar through the rendering engine, the layout system, and the standard library.

Pax Designer goes open source

Along with this Beta launch we are open-sourcing Pax Designer, Pax’s integrated vector design tool — which itself was built 100% in Pax.

That makes Pax Designer a solid reference example of Pax in production.  Pax Designer is already running on our website pax.dev, but this hosted preview doesn’t yet sync code — you must currently run Pax Designer locally to try out reading & writing code with the designer.

What's next?

We're working on a fully-featured hosted version of Pax Designer, which will become Pax Pro — a team collaboration tool that enables non-developers to make visual contributions to GitHub repos hand-in-hand with developers. 

We are also working on Pax JavaScript, bindings that will allow pax-lang to attach to JavaScript/TypeScript application logic as an alternative to Rust. 

Other features and fixes will be a function of user feedback. Please take it for a spin, build something, and let us know what you think!  See a partial list of current features on the GitHub README.

Pax today in Beta is far from perfect, but we're proud of how far it's come and excited about where it's headed. We hope some folks here will share our excitement, or even join us in our mission to make software creation more creative and accessible to more of humanity.
- https://old.reddit.com/r/rust/comments/1fdmjzl/pax_enters_beta_rust_guis_with_an_integrated/

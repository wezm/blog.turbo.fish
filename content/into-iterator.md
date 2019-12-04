+++
title = "Why does IntoIterator have two associated types?"
date = 2019-12-04
draft = true
+++

In this post, I am going to look at a simple question: why does Rust's
`IntoIterator` trait have two associated types; why do implementers need to
declare the `Item` type when it's already present on the `IntoIter` type's
`Iterator` implementation?

This is something I started thinking about as a result of wanting to write a
blog post about trait bounds on associated types of associated types. This post
doesn't touch on that topic, but you can probably expect that to be the next
post on this blog 🙂

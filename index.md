# Ruby Changes

- [Ruby 3.0 - Dec 25th, 2020 - What's News?](#ruby-30---dec-25th-2020---whats-news)
- [Ruby 3x3 - Ruby 3 Will Be 3 Times Faster - What's News?](#ruby-3x3---ruby-3-will-be-3-times-faster---whats-news)
- [Ruby 2.6 - Dec 25th, 2018 - What's News?](#ruby-26---dec-25th-2018---whats-news)
- [Ruby 2.5 - Dec 25th, 2017 - What's News?](#ruby-25---dec-25th-2017---whats-news)



## Ruby 3.0 - Dec 25th, 2020 - What's News?

An awesome collection about ruby 3.0 news:

{% include ruby30.html %}



## Ruby 3x3 - Ruby 3 Will Be 3 Times Faster - What's News?


### Q: What's 3x3?

_3x3 => Ruby 3 will be 3 times faster in 2020_

Ruby 3 - the next major update of ruby (planed for 2020) will be 3 times (3x) faster than Ruby 2.

Note: The baseline for Ruby3x3 is 2.0 so all the improvements in 2.x will count toward the 3x goal.


### Q: What's OptCarrot? [:octocat:](https://github.com/mame/optcarrot)

_A Nintendo Entertainment System (NES) emulator written in Ruby - running with 60 frames per seconds (fps) in Ruby 3 in 2020_

An "enjoyable" benchmark for rubies to drive "Ruby 3x3: Ruby 3 will be 3 times faster".

The benchmark is a Nintendo Entertainment System (NES) emulator that works at 20 frames per seconds (fps) in Ruby 2.0.
An original NES works at 60 fps. If Ruby 3x3 succeeds, we can enjoy NES games with ruby!

NOTE: We do not aim to create a practical NES emulator.
There are many great emulators available today.
We recommend using another emulator if you want to play a game.

**Benchmark example**

![](https://raw.githubusercontent.com/mame/optcarrot/master/doc/benchmark-summary.png)

See [Rubies Benchmark with Optcarrot](https://github.com/mame/optcarrot/blob/master/doc/benchmark.md) for the measurement condition and some more charts.


### Major News

- 2018/Feb - [Ruby 2.6.0 Preview Released](https://www.ruby-lang.org/en/news/2018/02/24/ruby-2-6-0-preview1-released) - Early 2.6.0 preview release incl. Just-In-Time (JIT) compiler; to use add `--jit` to the command line
- 2017/Dec - [MJIT infrastructure accepted into Ruby 2.6](https://github.com/ruby/ruby/pull/1782) - MJIT infrastructure means: JIT worker thread, profiler, gcc/clang compiler support, loading function from shared object file, some hooks to ensure JIT does not cause SEGV, etc...

See the [#Ruby3x3](https://twitter.com/hashtag/Ruby3x3) hashtag on twitter for the latest Ruby 3x3 news bytes.


### Articles

An awesome collection about ruby 3x3 news, benchmarks and more:

{% include ruby3x3.html %}



## Ruby 2.6 - Dec 25th, 2018 - What's News?

An awesome collection about ruby 2.6 news:


{% include ruby26.html %}



## Ruby 2.5 - Dec 25th, 2017 - What's News?

An awesome collection about ruby 2.5 news:

{% include ruby25.html %}
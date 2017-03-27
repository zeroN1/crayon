# crayon
/*
  * Simple animation toolkit for web based animation
  * ------------------------------------------------
  * @dependencies:
  *  @node.js,
  *  @express.js,
  *  @phaser.js
  *  @angular.js
  * ---------------------------------------------------------------------------------------------------------
  * @description:
  *   This utility wrapper collections is aimed at rapidly prototyping 
  *   quick desing ideas into a fully featured 2D/3D animation. In order
  *   to maintain a high-level wrapper that encompasses required functionalities
  *   from the listed dependencies into Specialized scenario generators that,
  *   uses texture maps, the draw logic, and events to bind together a environment
  *   runs the game using the user's agent and, maintain sporadic req/res cycles with
  *   for async map updates between the levels. 
  * ----------------------------------------------------------------------------------------------------------
  * @structure:
  *   @httpServer:
  *     @serves: static template, AI heuristics, physics maps, texture atlasses, JSON and HTML
  *   @statics:
  *     @texture atlases, atlas maps (JSON)
  *     @UI assets
  *     @Presentational assets (like pure html/text content for about us, the usuals ...)
  *   @gamelooper:
  *     @listens for user events,
  *     @maps events to actions
  *     @generate map change
  *     @render map portion with change
  *     @loop reset
  *   @AtlasMapper:
  *     @atlas path
  *     @tile size (w,h), start (x,y)
  *     @some basic tile properties (like the rotated or inverted variation of a base tile)
  *     @maintains a JSON/BSON map for each atlas
  * -----------------------------------------------------------------------------------------------------------
*/

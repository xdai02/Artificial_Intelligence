# Pacman Usage

1. Play Pacman in keyboard mode

    ```
    python pacman.py
    ```

2. See help and usage

    ```
    python pacman.py -h
    ```

3. Find a path to coordinate (1, 1) using Depth First Search

    ```
    python pacman.py -l mediumMaze -p SearchAgent -a fn=dfs
    ```

4. Find a path to coordinate (1, 1) using Breadth First Search

    ```
    python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
    ```

5. Find a path to coordinate (1, 1) using Uniform Cost Search

    ```
    python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs
    ```

6. Find a path to coordinate (1, 1) with lower cost to move East

    ```
    python pacman.py -l mediumDottedMaze -p StayEastSearchAgent
    ```

7. Find a path to coordinate (1, 1) with lower cost to move West

    ```
    python pacman.py -l mediumScaryMaze -p StayWestSearchAgent
    ```

8. Eat all food using Closest Dot Search

    ```
    python pacman.py -l bigSearch -p ClosestDotSearchAgent
    ```

9. Eat all food against monsters

    ```
    python pacman.py -p ReflexAgent
    ```
